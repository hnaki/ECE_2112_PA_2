# EXPERIMENT 2: NUMERICAL PYTHON (NUMPY)

#### Name: Barretto, Aron Caleb R.

#### Section: 2ECE-D

#### Date Submitted: September 4, 2024

### I. Intended Learning Outcomes:
1. To identify the codes and functions incorporated in the Numpy library
2. To be able to apply and use the different codes and functions in creating a Python program using a
Numpy library

### II. Instructions:
Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter
notebook in the dedicated submission bin.

## Documentation

### 1. NORMALIZATION PROBLEM: 
Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation. Mathematically, normalization can be
expressed as:

![image](https://github.com/user-attachments/assets/7ae30fae-b0d4-4476-b6f8-9c078612c129)

In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls.
In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized
ndarray as X_normalized.npy

### Code:

![image](https://github.com/user-attachments/assets/de7a29b1-bab6-405a-b991-fae1e1b104e9)

The program will generate a random 5 by 5 array, which will then be normalized after finding the mean and standard deviation. The normalized array will then be saved in a .npy file.

### Example Output:

![image](https://github.com/user-attachments/assets/a8b61083-42ac-4484-9c2f-945dfad2eb85)

![image](https://github.com/user-attachments/assets/7a72513e-3fde-4083-834d-2417df50bf09)

### 2. DIVISIBLE BY 3 PROBLEM:
Create the following 10 x 10 ndarray.

![image](https://github.com/user-attachments/assets/ccb7076b-626c-4af0-ba73-3f1b9523e880)

which are the squares of the first 100 positive integers.

From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

### Code:

![image](https://github.com/user-attachments/assets/a31447c1-836b-4b92-8066-f94d7820629a)

This program will generate an arranged array from 1 to 100 and will be reshaped in a 10 by 10 2D dimensional array. The values will be the squares of the first 10 positive integers. After that, the program will determine the integers that are divisible by 3 and will be placed in another array.

### Output:

![image](https://github.com/user-attachments/assets/9674983a-a83d-4f0b-bc25-e2636592dd37)

![image](https://github.com/user-attachments/assets/f0e5cfae-f8d7-42f1-9000-c48cf8fa835b)


