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
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: R mounish vamsi kumar
#RegisterNumber: 24003774
import numpy as np
A = np.array([[1, -3],
              [3,  1]])
B = np.array([0, 10])
solution = np.linalg.solve(A, B)
print(np.round(solution, 1))
```

## Output:
<img width="1920" height="1140" alt="Screenshot 2026-02-07 103006" src="https://github.com/user-attachments/assets/fc643a9f-58eb-4891-9c74-673eb48d9122" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

