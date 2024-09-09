# EXPERIMENT 2: NUMERICAL PYTHON (NUMPY)
## Submitted By: DOMINGO, Mariedel O.  
## Section: 2ECE-A
# I. Intended Learning Outcomes
### In this experiment, the primary objective is to develop a Python code within the Jupyter notebook, utilizing the Numpy library to address the provided problems.
# II. Instructions
## Problem 1: NORMALIZATION PROBLEM
### Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as: Z = (matrix - mean)/standard_deviation. In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and .std() calls. In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy 
## Problem 2: DIVISIBLE BY 3 PROBLEM
### Create the following 10 x 10 ndarray. which are the squares of the first 100 positive integers. From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy
# III. Solution
## Problem 1: NORMALIZATION PROBLEM
### Normalization is a fundamental data preprocessing technique used in statistics and various other fields. In this problem, the NumPy library will be utilized, with np.random.random employed to generate random values for the array. Additionally, np.mean and np.std will be used to calculate the mean and standard deviation necessary for calculating the normalized values using the formula  Z = (matrix - mean)/standard_deviation. The normalized array will then be saved to a file named "X_normalized.npy," providing efficient and compact storage for numerical data.
###
### In summary, the required outcomes are as follows:
#### 1. Generate a random 5x5 NumPy array
#### 2. Calculate its mean and standard deviation
#### 3. Normalize the array by centering and scaling
#### 4. Save the normalized array as X_normalized.npy.
###
### CODE:
![image](https://github.com/user-attachments/assets/8772fa5e-9842-41df-8482-f873723d9773)
###
### OUTPUT:
![image](https://github.com/user-attachments/assets/4f576302-8115-4d51-b064-bc45b62d5adb)
## Problem 2: DIVISIBLE BY 3 PROBLEM
### In Problem 2, the main objective is to first create a 10x10 array containing the squares of the first 100 positive integers. This is achieved using the NumPy library by employing np.arange to specify the integers and np.reshape to format the array into 10x10. After creating the array, the next step is to identify elements divisible by 3. This is done using the function div_by_3 = A[A % 3 == 0], where A % 3 calculates the remainder when each element in the array A is divided by 3, and A % 3 == 0 creates a boolean mask to filter elements with a remainder of 0. Finally, the result is saved as "div_by_3.npy."
###
### In summary, the required outcomes are as follows:
#### 1. Create a 10 x 10 ndarray containing the squares of the first 100 positive integers.
#### 2. Identify all elements in this ndarray that are divisible by 3.
#### 3. Save the resulting array of these elements as div_by_3.npy.
###
### CODE:
![image](https://github.com/user-attachments/assets/9b8b9388-ab35-4fd9-aa33-607a22c1037d)
###
### OUTPUT:
![image](https://github.com/user-attachments/assets/94085efe-90b8-4c96-bdb6-f7fb84d46a95)





