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
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.array([-9,4,-1])
le = np.linalg.solve(A,B)
print(le)

```
## Output:
![Screenshot 2023-12-15 205140](https://github.com/jagadeesh9500/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149087921/7896c8d3-39ef-47ce-8fe5-2c4742cb7e31)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

