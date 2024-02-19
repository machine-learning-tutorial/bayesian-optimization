# Material for this tutorial
- The theoretical lecture can be found here
- The tutorial in slide form is here

# Installation instructions

## Get the repository with Git
You will need to have Git previously installed in your computer.
To check if you have it installed, open your terminal and type:

``` bash
git --version
```

### Git installation in mac

``` bash
brew update
brew install git
```

### Git installation in linux
#### Ubuntu/Debian

``` bash
sudo apt install git
```

#### CentOS

``` bash
sudo yum install git
```

Once you have Git installed open your terminal, go to your desired directory, and type:
``` bash
git clone https://github.com/machine-learning-tutorial/bayesian-optimization.git
cd bayesian-optimization
```

## Get the repository with direct download
Open your terminal, go to your desired directory, and type:
``` bash
wget https://github.com/machine-learning-tutorial/bayesian-optimization/archive/refs/heads/main.zip
unzip main.zip
cd bayesian-optimization
```

## Install required libraries in a virtual environment
You need to install the dependencies before running the notebooks.

### Using conda

If you don't have conda installed already and want to use conda for environment management, you can install the miniconda as [described here](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html).

- Create a conda env with `conda create -n bo-tutorial python=3.10`
- Activate the environment with `conda activate bo-tutorial`
- Install the required packages via `pip install -r requirements.txt`.

### Using venv only

If you do not have conda installed:

Alternatively, you can create the virtual env with `venv` in the standard library

```bash
python -m venv nn-tutorial
```

and activate the env with `source <venv>/bin/activate` (bash) or `C:> <venv>/Scripts/activate.bat` (Windows)

Then, install the packages with pip within the activated environment

```bash
python -m pip install -r requirements.txt
```

Afterwards, you should be able to run the provided notebooks.

## Running the tutorial

After installing the package

You can start the jupyterlab in the terminal, and it will start a browser automatically

```bash
jupyter lab
```

Alternatively, you can use supported Editor to run the jupyter notebooks, e.g. with VS Code.
