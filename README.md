# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
## Program:
# Register No: 212225230078
# Developed By: Gokulan S
# 1-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print("{:.2f}".format(result))
```

# Infinity Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(result))
```

## Output:
### 1-Norm of a Matrix
<img width="370" height="161" alt="image" src="https://github.com/user-attachments/assets/60c687be-758d-4e19-ae6a-315e1b7bdae6" />


### 2-Norm of a Matrix
<img width="430" height="290" alt="image" src="https://github.com/user-attachments/assets/0a188295-0a09-4a9f-9617-e6f484857fc9" />


### Infinity Norm of a Matrix
<img width="320" height="144" alt="image" src="https://github.com/user-attachments/assets/3f044a14-59ed-424b-a290-ca19696cc672" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
