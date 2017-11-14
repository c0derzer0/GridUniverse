# RL_problems

Repository created with the goal of developing reinforcement learning algorithms and be able to reproduce 
experiments for different environments. Currently working exclusively on OpenAI gym.

## Example of use
Currently no example available only a test example is available to check if the environment works correctly. You can run
it by going to the main directory of the repository and entering the command:

`python atari_example.py`

You should see a small window that automatically plays "Space Invaders" if everything is working correctly.

## Installation

### Requirements
You need to have installed the following packages before starting with the set up of the environment for this project:
- cmake
- zlib1g-dev
- libjpeg-dev
- xvfb
- libav-tools
- xorg-dev
- libboost-all-dev
- libsdl2-dev
- swig

To install them you can follow the explanations given in the official repository:
https://github.com/openai/gym#installation

If you already have them you can skip this step. An explanation on how to set up your virtual environment is given
provided that you are using Anaconda.

### Create conda environment

First you need to install Anaconda. Select your corresponding installation file for Python 3.6. version following 
the instructions that can be found on the official Mkdocs documentation.
https://conda.io/docs/user-guide/install/index.html

Make sure you add conda to your system environment variables during installation, otherwise do it manually afterwards.
You can check that the installation was successful by opening a terminal and enter one of the following commands:

```
conda --help
```

### If it is your first time using this repository, or you would like to create a new environment for using it:

Open a terminal, go to the main directory of the repository and enter one of the following commands:

For installation on default path (/home/<username>/anaconda3/envs/<new_environment_name>):  
`conda env create -n <new_environment_name> -f repository_dir/requirements.yml`

For installation on another path:  
`conda env create -p c:/path/to/installation/folder/<new_environment_name> -f repository_dir/requirements.yml`

For more information on this command, please check the official documentation:  
https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file

### If you already have an existing conda environment and only want to update the corresponding packages:

`conda env update -n <name_of_environment_to_update> -f repository_dir/requirements.yml`

For more information on this command, please check the official documentation.
https://conda.io/docs/commands/env/conda-env-update.html

## Installation of OpenAI gym

Currently OpenAI Gym is supported only in Linux distributions.

### Activate the conda environment and install the required packages entering the following commands:

`source activate <name_of_environment>`

`pip install 'gym[all]'`

Now you should be able to run `atari_example.py`.

For a general documentation on how the environment works refer to the official documentation on
https://gym.openai.com/docs

## API Reference

Currently the only documentaiton is this readme. In the future, you will be able to find further information in the docs folder.

## Tests

Run `atari_example.py` to make sure that everything is in place and works as it should.

## Contributors

Currently not looking for help from contributors. Further information to be added in the future.

## License

For information about the license of this code please refer to the corresponding file "license.txt"
