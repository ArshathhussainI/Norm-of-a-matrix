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
# Register No: 24008800
# Developed By: ARSHATH HUSSAIN I
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
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-07 125417](https://github.com/user-attachments/assets/faf21e0d-6509-456c-b73b-652affe223c9)


### 2-Norm of a Matrix
![Screenshot 2024-12-07 125428](https://github.com/user-attachments/assets/f44765e5-68b4-4316-9879-61dbeb68c939)

### Infinity Norm of a Matrix
![Screenshot 2024-12-07 125440](https://github.com/user-attachments/assets/1ce34de8-e5f4-485f-80eb-6437684ba0ff)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
