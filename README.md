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
#1-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: Mohammed Faizal
#RegisterNumber: 22003412
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


```python
#2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: Mohammed Faizal
#RegisterNumber: 22003707
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


```python
# Infinity Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: Mohammed Faizal
#RegisterNumber: 22003412
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120553195/215327365-cec9bebf-c66d-4efd-a024-54e40f1c3e25.png)
<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120553195/215327392-734b9477-2c02-4a83-a8f5-80fa17dc1182.png)
<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/120553195/215327416-d85ed2a0-b597-4061-8a93-2391f88d52d1.png)
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
