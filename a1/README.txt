SENG 474 A02: Data Mining
Assignment 1 Experiment Code
Sean McAuliffe, V00913346
Feb 3, 2021

The experiments were performed using python in a Jupyter notebook.
The code is available as a .ipynb file provided with this report.
In order to run the code and replicate the reported results, please ensure
you have the required binaries installed and available in your PATH.

Required binaries:
- python3
- pip3
- jupyter
- graphviz

Required python packages:
- numpy
- pandas
- matplotlib
- graphviz
- sklearn
- scipy

The required pythong packages are installed at the beginning of the notebook.
The code is divided into sections, each section is preceded by a markdown cell
explaining the purpose of the section.

The first section is for data preparation. The data is loaded from the provided
cleaned_adult.csv file. The order of the rows are shuffled after being loaded
into memory. The data is then split into training and test sets. The training
set is 80% of the provided data by default, and the remaining 20% is used as
the test set.

The second section provides code which trains a decision tree classifier
model to the provided data, varying search hyperparameters, and the training
set size.