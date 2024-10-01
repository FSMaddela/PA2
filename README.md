
# Programming Assignment 2 - Numerical Python

This project is a submission for my programming assignment which makes use of Numerical Python or Numpy. Included are 2 problems involving arrays and mathematics. 

## Problem 1: Normalization Problem

The first problem involves one of the most basic preprocessing techniques in 
data analytics. The problem requires the creation of a random 5 x 5 ndarray stored in variable X. After which X is normalized and saved as X_normalized.npy.

**Solution**
Create a random 5 x 5 ndarray using the syntax:

`np.random.rand(5, 5)`

Normalize the ndarray by solving for the mean and std then use the following formula:

`(X - mean) / std`

Save output using `np.save`

## Problem 2: Divisible by Three Problem

The second problem requires a 10 x 10 ndarray to be filled with squares of the first 100 integers. After filling the 10 x 10 ndarray, all elements that are divisible by 3 are identified and saved as div_by_3.npy.

**Solution**
Create a 10 x 10 ndarray using the following syntax:

`np.arange(1, 101).reshape(10, 10) ** 2 `

Identify the elements divisible by 3 using the equation:

`X % 3 == 0`

Save output using `np.save`

## Version History

v1.0 - Initial upload <br/>
v2.0 - Included markdowns for readability
