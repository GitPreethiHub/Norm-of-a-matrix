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
# Register No: 212222100037
# Developed By: Preethi M
# 1-Norm of a Matrix
mport numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,1)
print("{:.2f}".format(norm))
# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,2)
print("{:.2f}".format(norm))
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
infinity=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(infinity))
```
## Output:
### 1-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/119475585/235293492-0a5be718-5083-4d3c-989a-54c7b37ab410.png)

### 2-Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/119475585/235293541-56ebab5d-e328-40b3-bfde-d96dda0b3a8f.png)


### Infinity Norm of a Matrix
<br>![image](https://user-images.githubusercontent.com/119475585/235293557-d7ad3bb2-6da9-4244-8385-003eff3df1a3.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
