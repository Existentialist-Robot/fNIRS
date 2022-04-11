# fNIRS

## Local env setup

### Clone Repo

Install Github Desktop
httpsdesktop.github.com
Clone this repository 
httpsgithub.comExistentialist-Robotkoalacademy_research_analytics
Navigate to 'documentsgithubkoalacademy_research_analytics' in your file system to confirm clone was successful

### Anaconda install and Environment Creation

Install Anaconda
httpswww.anaconda.comproductsindividual

Open anaconda terminal by one of the two following methods

![conda_1](https://github.com/Existentialist-Robot/fNIRS/blob/main/Images/conda_1.PNG)

or 

![conda_2](https://github.com/Existentialist-Robot/fNIRS/blob/main/Images/conda_2.PNG)

Once you have opened an anaconda terminal, navigate to the root of the repo directory you just cloned by the following command

```
cd full filepath of repo
```

for example

```
cd Users/eredm/Documents/GitHub/koalacademy_research_analytics
```

Press enter to run the command.

If successful, your 'current working directory' is NOW in your local clone of the repo.

From here we will create a virtual environemnt and install the required packages from the environment.yml file, by running the following command in our conda terminal

```
conda env create -f environment.yml
```
Press enter to run the command.

Activate your virtual environment

```
conda activate koalacademy_research
```

You may be prompted with a YN - enter Y and press enter to execute the command

If successful, this command (among other things) should have install the Spyder framework - a python IDE (integrated development environment)

To enter this framework - from the anaconda terminal you type the following command

```
spyder
```

Press enter to run the command.

This should open the framework.

![spyder_1](https://github.com/Existentialist-Robot/fNIRS/blob/main/Images/spyder_1.PNG)

