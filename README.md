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
# Register No:212224230198
# Developed By:R Prabanjan
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-05-13 101401](https://github.com/user-attachments/assets/98f11b0e-1d4f-4dda-882e-f68ee2b83726)



### 2-Norm of a Matrix
![Screenshot 2025-05-13 101413](https://github.com/user-attachments/assets/0df774a3-1b7f-4730-ab4d-15a850c20caa)


### Infinity Norm of a Matrix
![Screenshot 2025-05-13 101427](https://github.com/user-attachments/assets/d0e03bd7-a23b-4dc6-9321-61735c9de80f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
