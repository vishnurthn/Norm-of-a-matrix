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
```
# Register No:212224240185
# Developed By:VISHNU RATHAN B
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix
<img width="641" height="237" alt="image" src="https://github.com/user-attachments/assets/085e7859-727e-49b2-a973-55ab04456661" />

### 2-Norm of a Matrix
<img width="703" height="326" alt="image" src="https://github.com/user-attachments/assets/a8be199d-0147-4bbe-b43f-9993a35bce7e" />

### Infinity Norm of a Matrix
<img width="763" height="355" alt="image" src="https://github.com/user-attachments/assets/bb395737-f591-4a56-b000-7d94af04e7c1" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
