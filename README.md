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
# Register No: 212224040239
# Developed By: Pranav Bhargav M
```
```
# 1-Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))

ans = np.linalg.norm(mat,1)
print("{:.2f}".format(ans))


```
```
# 2-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans = np.linalg.norm(mat,2)

print("{:.2f}".format(ans));

```
```
# Infinity Norm of a Matrix


import numpy as np

mat=np.array(eval(input()))

inv=np.linalg.norm(mat,ord=np.inf);
print("{:.2f}".format(inv))


```
## Output:
### 1-Norm of a Matrix
<img width="1215" height="928" alt="image" src="https://github.com/user-attachments/assets/a5548460-2057-4560-8e17-74aa89de94dc" />


### 2-Norm of a Matrix
<img width="1119" height="803" alt="image" src="https://github.com/user-attachments/assets/739eb502-11b2-4ce4-868e-717b1797560b" />


### Infinity Norm of a Matrix
<img width="865" height="814" alt="image" src="https://github.com/user-attachments/assets/f826cd0f-5101-4f54-acf1-59daa76e7060" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
