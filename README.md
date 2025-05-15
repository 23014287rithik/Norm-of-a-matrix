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
# Register No:21223230171
# Developed By:RITHIK V
# 1-Norm of a Matrix

'''devloped by:RITHIK V
REG NO:23014287
'''
import numpy as np
matric=np.array(eval(input()))
result=np.linalg.norm(matric,1)
print(result)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: RITHIK V 
RegisterNumber:23014287 
'''
import numpy as np
matric=np.array(eval(input()))
result=np.linalg.norm(matric,2)
print("{:.2f}".format(result))




# Infinity Norm of a Matrix


import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/cd84fd90-34e0-483b-8c6a-c82b7e788ad1)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/8ddbdc66-31aa-482d-9d86-e84e36799203)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/905d04df-b89d-4aae-b80c-39a4ce63d262)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
