# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn, PyTorch and Keras.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras.
* Reference solution: (not published yet)
    * [`numpy_matplotlib_sklearn_solution.ipynb`](numpy_matplotlib_sklearn_solution.ipynb)
    * [`pytorch_solution.ipynb`](pytorch_solution.ipynb)
    * [`keras_solution.ipynb`](keras_solution.ipynb)

# Requirements
Code tested on following environments, other version should also work:
* linux system (ubuntu 16.04) 
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1
* keras 2.1.2

# For students from SJTU
Please read [HEAR](EE369.md).

# The structure I used

I use the Lenet-5 with 2 convolution layers and 2 connection layers.

# The train and test accuracy

The training and test accuracy for 5 questions:

|      | train accuracy | test accuracy |
| ---- | -------------- | ------------- |
| Q1   | 0.9751667      | 0.878         |
| Q2   | 0.8161667      | 0.817         |
| Q3   | 0.9786667      | 0.863         |
| Q4   | 0.9813333      | 0.941         |
| Q5   | 0.9978777      | 0.989         |

