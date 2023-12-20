# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
### Program:
# Program to find the solution for the given linear equations.
# Developed by: DHANUSYA K 
# RegisterNumber: 23006651
```
import numpy as np
A=np.array([[5, -3,-10],[2, 2, -3],[-3, -1, 5]])
B=np.array([-9, 4, -1])
solution = np.linalg.solve(A, B)
print(solution)
```

## Output:
![Screenshot 2023-12-20 110448](https://github.com/Dhanu654/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148514965/175af9be-ffe1-4b37-8d47-b34e5a595aa7)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

