# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## AIM :

To write a python program to find a solution to a system of linear equations.

## EQUIPMENTS REQUIRED :
1. 	Hardware – PCs  
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner  

## ALGORITHM :  

### Step 1: 

Import the numpy module to use the built-in functions for calculation

### Step 2: 

Prepare the lists from each linear equations and assign in np.array()

### Step 3: 

Using the np.linalg.solve(), we can find the solutions.

### Step 4: 

End the program

## PROGRAM :


#Program to find the solution for the given linear equations.  
#Developed by: MIDHUN AZHAHU RAJA P  
#RegisterNumber: 22008311  
import numpy as np  
A=np.array([[1,3],[2,5]])  
B=np.array([5,-3])  
sol=np.linalg.solve(A,B)  
print(sol)  

## OUTPUT :

![Screenshot_20230108_113851](https://user-images.githubusercontent.com/118054670/211192161-4cf6434c-9ebb-4bc4-a0d5-1d5f90da578b.png)

## RESULT : 

Thus the solutions for the linear equations are successfully solved using python program

