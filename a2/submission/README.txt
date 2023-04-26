SENG 474 A02: Data Mining
Assignment 2 Experiment Code
Sean McAuliffe, V00913346
Feb 27, 2021

The experiments were performed using python in a Jupyter notebook.
The code is available as a .ipynb file provided with this report. 
This implementation also makes use of a utility function provided with
the Fasion-MNIST dataset, the relevant code has been included in the utils/
folder in this repository.

In order to run the code and replicate the reported results, please ensure
you have the required binaries installed and available in your PATH.

Required binaries:
- python3
- pip3
- jupyter

Required python packages:
- numpy
- matplotlib
- sklearn

The required pythong packages are installed at the beginning of the notebook.
The code is divided into sections, each section is preceded by a markdown cell
explaining the purpose of the section.

The first section is for data preparation. The data is loaded using mnist_read 
from the MNIST dataset. The MNIST dataset has not been provided with this submission.

It can be downloaded from https://github.com/zalandoresearch/fashion-mnist/archive/master.zip
Please ensure that the data/ directory from this .zip file is present in the same
directory as the notebook when running.