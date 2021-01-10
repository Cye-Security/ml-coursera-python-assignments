# Python Programming Assignments for Coursera ML

This repository contains the python versions of the programming assignments for the [Coursera Machine Learning online class](https://www.coursera.org/learn/machine-learning). The course is one of the most popular and approachable courses available, but its programming assignments are in MATLAB or OCTAVE. As Python is the current standard in ML, we will implement the course assignments using it instead.

The re-written assignments work seamlessly with the class and do not require any of the materials published in the MATLAB assignments. Here are some new and useful features for these sets of assignments: 

- The assignments use [Jupyter Notebook](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html), which provides an intuitive flow easier than the original MATLAB/OCTAVE assignments.
- The re-written instructions are now embedded within the Jupyter Notebook along with the `python` starter code. For each assignment, all work is done solely within the notebook.
- The `python` assignments can be submitted for grading. They were tested to work perfectly well with the original Coursera grader. 
- After each part of a given assignment, the Jupyter Notebook contains a cell which prompts the user for submitting the current part of the assignment for grading.  

## Instructions

1. To get started, clone or download the repo. Each assignment is contained in a separate folder, containing two files: 
 - The assignment `jupyter` notebook, which has a `.ipynb` extension. *All the code which you need to write will be written within this notebook*.
 - A python module `utils.py` which contains some helper functions needed for the assignment. Functions within the `utils` module are called from the python notebook. *You do not need to modify or add any code to this file*.

2. Install the requirements (`pip3 install -r requirements.txt`). We recommend using at least versions specified in `requirements.txt`, or later. The project also contains a `environment.yml` file if you wish to use `conda`. Make sure your Python version is at least `3.6.4`, Python 2 is not supported. So far the excercises were tested on (feel free to add your in a pull request):
    * Python 3.8.5 @ WSL2 Ubuntu 20.04 

3. You can now start working on the assignments. Navigate to the directory of the current assignment, and launch the jupyter notebook from the terminal using `jupyter notebook` and open the link specified in the terminal. Click the `.ipynb` file to actually open the notebook ans start working.


## Optional Tutorials

- [Numpy and matplotlib tutorial](http://cs231n.github.io/python-numpy-tutorial/): We will be using numpy extensively for matrix and vector operations. This is great tutorial to get you started with using numpy and matplotlib for plotting.

- [Jupyter notebook](https://medium.com/codingthesmartway-com-blog/getting-started-with-jupyter-notebook-for-python-4e7082bd5d46): Getting started with the jupyter notebook. 

## Caveats and tips

- In many of the exercises, the regularization parameter $\lambda$ is denoted as the variable name `lambda_`.

-  In `numpy`, the function `dot` is used to perform matrix multiplication. The operation '*' only does element-by-element multiplication (unlike MATLAB). If you are using python version 3.5+, the operator '@' is the new matrix multiplication, and it is equivalent to the `dot` function.

