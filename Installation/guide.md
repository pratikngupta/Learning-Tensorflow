# Installation Guide

This document will help to install the required packages for the project.

# Conda Environment
### What is Conda?
Conda is an open source package management system and environment management system that runs on Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their dependencies. Conda easily creates, saves, loads and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

### Advantages of Conda
- Conda is a package manager, an environment manager, a Python/R data science distribution and a collection of over 720+ open source packages.
- Conda is a free and open source software.
- Conda is cross-platform.
- Also each environment can have its own version of Python installed which is very useful for testing code with different versions of Python and its packages.

### What is mini-conda?
MiniConda is a free minimal installer for conda. It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others. It is intended for users who are familiar with conda and just need the tools to create their own environments.


### How to install MiniConda?
- Download the installer from [here](https://conda.io/miniconda.html).
- Run the installer.
- Follow the instructions on the installer screens.
- Open a terminal window.
- Type the following command to verify that conda is available on mac:
```bash
conda list
```

# Installation on macOS

Install xcode from the terminal:
```bash
xcode-select --install
```

Install Juptyer Notebook:
```bash
conda install -y jupyter
```

There are two ways to install Tensorflow on macOS:
- Install Tensorflow without Metal support
```bash
# clone the repository
git clone https://github.com/pratikngupta/Learning-Tensorflow.git
# change the directory
cd Learning-Tensorflow/Installation
ls
printf ("Installing Tensorflow without Metal support\n")

conda env create -f tensorflow_on_mac.yml --name tensorflow

# activate the environment
conda activate tensorflow
```


- Install Tensorflow with Metal support






# Installation on Windows



# Installation on Linux
