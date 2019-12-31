# CuDNN Image Filtering via PyTorch
A tutorial for basic spatial filtering of imagery on the GPU using PyTorch. This is an easy way to complement and accelerate traditional numpy/scipy/OpenCV image processing or image synthesis workflows

## Installation

### Requirements

This project requires the following for GPU support:

Python3.6 or greater
An NVIDIA graphics card that supports CUDA 10 and is greater than ... in compute power (link to table of existing cards to aid user in checking)
The ability to install necessary CUDA toolkits, libraries, and SDKs as needed by PyTorch

### Install CUDA, CUDA Toolkits, and CuDNN

(link to pytorch website) --> may involve setting up NVIDIA Developer account

### Project installation and Virtual Environment Setup 

*On Linux*

```bash
# Navigate to desired project location
cd my/project/directory

# Checkout project
git checkout https://github.com/RyanHartzell/cudnn-image-filtering.git
cd cudnn-image-filtering

# Set up Python virtual environment assuming Python 3.6 or greater (X below refers to your major revision of Python)
python3.X -m venv venv_gpufiltering
source venv_gpufiltering/bin/activate
pip install -r requirements.txt
```

*On Windows*

```shell
# Navigate to desired project location
chdir my/project/directory

# Checkout project
git checkout https://github.com/RyanHartzell/cudnn-image-filtering.git
chdir cudnn-image-filtering

# Set up Python virtual environment assuming Python 3.6 or greater (X below refers to your major revision of Python)
python3.X -m venv venv_gpufiltering
venv_gpufiltering/Scripts/activate.bat
pip install -r requirements.txt
```

## Execution

Run the Jupyter Notebook cell by cell from Jupyter!

```bash
jupyter notebook "notebooks/CuDNN Image Filtering Tutorial Using PyTorch.ipynb"
```
