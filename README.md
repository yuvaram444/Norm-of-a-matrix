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
# Register No:24900232
# Developed By:Yuvaram
# 1-Norm of a Matrix
import numpy as np
n=np.array(eval(input()))
a=np.linalg.norm(n,1)
norm="{:.2f}".format(a)
print(norm)


# 2-Norm of a Matrix
import numpy as np
n=np.array(eval(input()))
a=np.linalg.norm(n,2)
norm="{:.2f}".format(a)
print(norm)


# Infinity Norm of a Matrix
import numpy as np
n=np.array(eval(input()))
a=np.linalg.norm(n,np.inf)
norm="{:.2f}".format(a)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-11-27 122337](https://github.com/user-attachments/assets/56fe6db6-5e53-4c33-9806-860c7eff1deb)
<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-11-27 122349](https://github.com/user-attachments/assets/93ce21df-3648-4336-bcce-15c5664e1434)
<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-11-27 122400](https://github.com/user-attachments/assets/85b59673-7161-4317-96cf-19aa92603099)
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
