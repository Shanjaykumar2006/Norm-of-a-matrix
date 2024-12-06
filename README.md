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
# Register No:
# Developed By:
# 1-Norm of a Matrix
...
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
...
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
![Screenshot 2024-12-06 150429](https://github.com/user-attachments/assets/ac62b3f7-9d7e-429a-be97-c6258cf1a53a)
![Screenshot 2024-12-06 150450](https://github.com/user-attachments/assets/b64de1b9-3924-4e02-af79-082a8895aff7)
![Screenshot 2024-12-06 150616](https://github.com/user-attachments/assets/b4095236-d96a-4532-be01-73319ca49885)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
