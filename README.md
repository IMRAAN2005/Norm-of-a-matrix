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
# Register No:  212223100053 
# Developed By:  SHAIK MAHAMMAD IMRAAN
# 1-Norm of a Matrix
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,1)
norm="{:.2f}".format(ans)
print(norm)



# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
norm="{:.2f}".format(ans)
print(norm)



# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,np.inf)
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/IMRAAN2005/Norm-of-a-matrix/assets/149347407/a3a01428-bdef-4195-b43a-463ff10d374e)

### 2-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/IMRAAN2005/Norm-of-a-matrix/assets/149347407/84018746-e844-477a-a183-e51591a57e78)

### Infinity Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/IMRAAN2005/Norm-of-a-matrix/assets/149347407/1a6a4048-0b52-4df7-9a9a-9109b0661545)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
### DEVELOPED BY: SHAIK MAHAMMAD IMRAAN
### REGISTER NO: 212223100053 
