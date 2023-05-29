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
```Python
# Register No:S.ROSELIN MARY JOVITA 
# Developed By: 212222230122
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:S.Roselin mary jovita
RegisterNumber: 212222230122
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
'''
program to find the Infinity of a matrix and display the result in two decimal places.
Developed by:S.Roselin mary jovita
RegisterNumber: 212222230122
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix


![NORM1](https://github.com/Roselinjovita/Norm-of-a-matrix/assets/119104296/68a4a07e-380a-4990-b351-796f29697e50)


### 2-Norm of a Matrix


![NORM2](https://github.com/Roselinjovita/Norm-of-a-matrix/assets/119104296/961c84f8-6794-4410-82d3-333c9139740a)


### Infinity Norm of a Matrix


![NORM3](https://github.com/Roselinjovita/Norm-of-a-matrix/assets/119104296/a8461257-5fc7-439f-a348-e61dc0d1c95b)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
