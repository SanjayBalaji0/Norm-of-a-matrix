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
# 1-Norm of a Matrix
##Program to find the 1-norm of a matrix
#Developed by:S.Sanjay Balaji
#Register no:23005804
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:S.Sanjay Balaji
RegisterNumber: 23005804
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
#Developed by:S.Sanjay Balaji
#Register no:23005804

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/SanjayBalaji0/Norm-of-a-matrix/assets/145533553/fadca921-0ab2-45cf-9f0c-6519906e1b84)


### 2-Norm of a Matrix
![image](https://github.com/SanjayBalaji0/Norm-of-a-matrix/assets/145533553/60981d1a-a4e9-4c4d-bd91-a6bbd63a5434)


### Infinity Norm of a Matrix
![image](https://github.com/SanjayBalaji0/Norm-of-a-matrix/assets/145533553/46d9bfc0-bcad-4951-a606-fcb29448e222)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
