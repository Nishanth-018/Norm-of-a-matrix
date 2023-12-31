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
# Register No:23007929
# Developed By:y66131
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:Nishanth J 
RegisterNumber:23007929
'''
import numpy as np

# Type your code here

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-31 233053](https://github.com/Nishanth-018/Norm-of-a-matrix/assets/149347651/71881f65-0915-4da8-b3a9-7752f71cf22e)


### 2-Norm of a Matrix
![Screenshot 2023-12-31 233215](https://github.com/Nishanth-018/Norm-of-a-matrix/assets/149347651/5cc733b5-0444-4567-9fed-3bf4f950434a)


### Infinity Norm of a Matrix
![Screenshot 2023-12-31 233314](https://github.com/Nishanth-018/Norm-of-a-matrix/assets/149347651/259848fe-9f9b-42ea-a66e-460bb411170e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
