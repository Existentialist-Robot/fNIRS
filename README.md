# fNIRS

## Local env setup

### Clone Repo

Install Github Desktop
https://desktop.github.com/
Clone this repository 
https://github.com/Existentialist-Robot/fNIRS
Navigate to 'documents/github/fNIRS' in your local file system to confirm clone was successful

### Anaconda install and Environment Creation

Install Anaconda
https://www.anaconda.com/products/distribution

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
cd Users/eredm/Documents/GitHub/fNIRS
```

Press enter to run the command.

If successful, your 'current working directory' is NOW in your local clone of the repo.

From here we will create a virtual environemnt and install the required packages from the fNIRS.yml file, by running the following command in our conda terminal

```
conda env create --file fNIRS.yml
```
Press enter to run the command.

You may be prompted with a 'Y/N' - enter Y and press enter to execute the command

Activate your virtual environment with the following command

```
conda activate fNIRS
```

If successful, this command (among other things) should have installed MNE and the Spyder framework - a scientific python IDE (integrated development environment)

To enter this framework - from the anaconda terminal you type the following command

```
spyder
```

Press enter to run the command.

This should open the framework.

![spyder_1](https://github.com/Existentialist-Robot/fNIRS/blob/main/Images/spyder_1.PNG)

You should be able to run the following command from the Spyder IPython Console

```
import MNE
```
