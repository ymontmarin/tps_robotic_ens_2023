# Robotic course, ENS, 2023

This repository contains the exercices for the robotics class at ENS, 2023.
The exercices are organized by notebook. Each notebook corresponds to one chapter of the class.
The notebooks are in Python and based on the software [Pinocchio](https://github.com/stack-of-tasks/pinocchio).

## Set up
### Clone this repository
Using git and ssh
```bash
git clone git@github.com:ymontmarin/tps_robotic_ens_2023.git
```
or https:
```bash
git clone https://github.com/ymontmarin/tps_robotic_ens_2023.git
```

### Install miniconda
On Linux or OSX only: https://docs.conda.io/en/latest/miniconda.html
Only a little snippet is applied tou your home .bashrc, everything else will be segmented !

Or use Anaconda on Windows and use conda prompt insteal of a terminal.

Go into the repository folder.

Open a terminal.

Create and activate conda environment:
```bash
conda env create -f robotic_course_env.yml
```
From now on, when you want to work on the TPs you only need to do:
```bash
conda activate robotic_course
```
And launch the notebook with:
```bash
jupyter-lab
```
Don't forget, the notebook is accessible from any browser using `localhost:8888` in the adress bar.
Meshcat visualisation can be access in full page in `localhost:700N/static/` where N denotes the Nth meshcat instance created with the running kernel.


### Update the notebooks

If the repository changes (for example when new tutorials are pushes), you need to update your local
version by "pulling" it from the repository.
On a native installation, just go in the folder containing the tutorials and execute ```git pull```.
