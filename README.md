# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
#Developed by:Boopathy S
#RegisterNumber: 2305003002

#i)Program to find 1-norm of a matrix.
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

#ii)Program to find 2-norm of a matrix.
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

#iii)Program to find infinity-norm of a matrix.
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-24 101735](https://github.com/BOOPATHYS0660/Norm-of-a-matrix/assets/155909381/ab175164-67b2-405f-8889-5a55dbd71b85)

### 2-Norm of a Matrix
![Screenshot 2024-05-24 101808](https://github.com/BOOPATHYS0660/Norm-of-a-matrix/assets/155909381/27a5be87-5fbb-41df-94fa-517e1ba7825b)

### Infinity Norm of a Matrix
![Screenshot 2024-05-24 101823](https://github.com/BOOPATHYS0660/Norm-of-a-matrix/assets/155909381/2ab2f30a-6e3e-4b31-b4f5-ff73ba3852b8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
