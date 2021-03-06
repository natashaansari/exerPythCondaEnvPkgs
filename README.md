# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Run the Conda commands shown in the video and describe them in the table below.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/N6806_Fall2020_DevNotes/blob/master/Projects/002%20-%20Practice%20Using%20Git%20and%20GitHub/README.md
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [ ] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.

## Conda Concepts

* [ ] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |Having a specific environment for each project without needing separate computers|
|What is the default package manager in Python?            |pip|
|How do you manage environments and packages in Anaconda?  |Conda does both|
|`conda list`       |lists all the default packages with Anaconda|
|`conda env list`       |lists all environments with Anaconda3|
|How do you keep your base environment unchanged?       |creating a new envrionment each time|
|What is the link to the Conda cheat sheet?     |https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf|
|`conda create --name XXXX`       |create a new environment|
|`source activate XXXX`       |how to start working in a different environment|
|`conda install YYYY`       |install packages into specific environments|
|channels in Conda       |how to find other packages outside of default|
|`conda install -c ZZZZ YYYY`       |how to look for packages in different channels (one time thing)|
|`conda config --show channels`       |shows which channel we are in|
|`conda config --add channels ZZZZ`       |how to add specific channels to channel list|
|conda-forge.org       |different page (channel) also offering packages|
|`source deactivate`       |how to remove an environment|
|`conda config --get channels`       |different priorities for conda to look for packages|

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

/opt/anaconda3/lib/python3.8/multiprocessing/resource_tracker.py:216: UserWarning: resource_tracker: There appear to be 1 leaked semaphore objects to clean up at shutdown
  warnings.warn('resource_tracker: There appear to be %d '
# conda environments:
#
base                  *  /opt/anaconda3
da35                     /opt/anaconda3/envs/da35


* What command would you use to remove the environments you created for this exercise from your computer?

conda deactivate
