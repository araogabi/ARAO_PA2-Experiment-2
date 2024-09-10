## **EXPERIMENT 2: NUMERICAL PYTHON (NUMPY)**

Author: ARAO, Angeline Jeannah E.
___________________________________________________________________________________________________________________________

## Background of the Experiment

Numerical Python (NumPy), is a tool in Python that helps with scientific computing. It allows you to work with large multi-dimensional 
arrays and matrices, and it also provides a wide collection of math functions to easily work with them.

## Objectives of the Experiment

1. To identify the codes and functions incorporated in the Numpy library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Numpy library

_Attached herewith is the Jupyter Notebook file where you can see the code for each problems._

## Problems

### **NORMALIZATION PROBLEM**
Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. 
Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as:
![image](https://github.com/user-attachments/assets/0aeedc79-4618-44ce-951d-0fa8d8f9c0fe)

In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and .std() calls. 

In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as _X_normalized.npy_

### **DIVISIBLE BY 3 PROBLEM**
Create the following 10 x 10 ndarray
![image](https://github.com/user-attachments/assets/b0f139ce-c29f-491b-86e2-fbdec23d3f07)

which are the squares of the first 100 positive integers.

From this ndarray, determine all the elements that are divisible by 3. Save the result as _div_by_3.npy_
___________________________________________________________________________________________________________________________
## Getting Started

### Tools Used
1. Anaconda Navigator
2. Jupyter Notebook

### Executing the Program
1. **Import Numpy** - Importing `NumPy` is essential because it provides efficient tools for numerical computations and array manipulation, enabling faster and more concise code execution. Without accessing `NumPy`, the code for these problems wouldn't run, as it is dependent on this library.
```
import numpy as np
```
2. **`Shift + Enter`** - To run the code, press `Shift + Enter` while the cell is selected, or click the `Run` button in the notebook toolbar. You will see the output below the cell.
___________________________________________________________________________________________________________________________
## Version History

**3.0** Updated the README file.  
**2.0** Added the README file.  
**1.0** Initial submission of the files.
