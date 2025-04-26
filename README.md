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
# Register No:212224230158
# Developed By:MIDHUN S
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
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
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-26 114557](https://github.com/user-attachments/assets/60a4062e-a281-47cb-8ca4-171847554c38)

### 2-Norm of a Matrix
![Screenshot 2025-04-26 114609](https://github.com/user-attachments/assets/d13e6573-01cf-4850-b638-86b9f5964272)

### Infinity Norm of a Matrix
![Screenshot 2025-04-26 114624](https://github.com/user-attachments/assets/fb533ab4-c517-4ea3-8ef9-00503ef43ab9)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
