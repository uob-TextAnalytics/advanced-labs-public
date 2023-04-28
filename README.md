# advanced-labs-public
This repository contains labs for text analytics as part of the unit Advanced Data Analytics, Spring 2023. 

For advanced text analytics, these lab notebooks are also your assessment, worth in total 30% of the unit. 

## Setting up your environment

The environment is set up in the same way as for Introduction to Data Analytics. You can reuse the same environment as for Introduction to Data Analytics, or set up a new one.

### Reusing the Intro Labs Environment

You will need the following additional packages, which you can install with Conda:

pytorch=1.10.2
scipy
transformers

You should specify '-c pytorch' to install Pytorch and '-c huggingface' to get the current version of transformers.

### Setting Up a New Environment

The instructions are the same as for the Introdcution to Data Analytics labs.
We recommend using ```conda``` to create an environment with the correct versions of all the packages you need for these labs. You can install either Anaconda or Miniconda, which will include the ```conda``` program. 

We provide a .yml file that lists all the packages you will need, and the versions that we have tested the labs with. You can use this file to create your environment as follows.

1. Open a terminal. Use the command line to navigate to the directory containing this notebook and the file ```crossplatform_environment.yml```. You can use the command ```cd``` to change directory on the command line.

1. Run the conda program by typing ```conda env create -f crossplatform_environment.yml```, then answer any questions that appear on the command line.

1. Activate the environment by running the command ```conda activate adv_data_analytics```. Note that the name of this environment is 'adv_data_analytics'.

1. Make kernel available in Jupyter: ```python -m ipykernel install --user --name=adv_data_analytics```.

1. Relaunch Jupyter: shutdown any running instances, and then type ```jupyter lab``` or ```jupyter notebook``` into your command line, depending on whether you prefer the full Jupyter lab development environment, or the simpler Jupyter notebook.

1. Find this notebook and open it up again.

1. Go to the top menu and change the kernel: click on 'Kernel'--> 'Change kernel' --> data_analytics.

You should now be ready to go!

The core libraries we will be using in this unit are:

- [Transformers](https://huggingface.co/docs/transformers/), produced by HuggingFace, is a library for using pretrained transformer models.
- [Pytorch](https://pytorch.org/docs/stable/index.html), a library for deep learning.

The libraries above have good documentation, which is available either online (links above) or via Python itself, e.g. `help(numpy.array)` in the Python interpreter. 

