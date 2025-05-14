# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Step1 : 
      Start the Python environment and import the NumPy library.
# Step 2: 
     Define the matrix using np.array().
# Step 3: 
    Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
# Step 4:
   Print the eigenvalues and eigenvectors and end the program.

# Program:

import numpy as np\
matrix = np.array([[4, -2],\
                   [1,  1]])\
eigenvalues, eigenvectors = np.linalg.eig(matrix)\
print("Eigenvalues of the matrix:", eigenvalues)\
print("Eigenvectors of the matrix:\n", eigenvectors)

## Output:
![Screenshot 2025-05-14 184651](https://github.com/user-attachments/assets/86869d7a-5429-4b92-8da1-262ffc371590)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
