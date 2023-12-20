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
# Register No: 212223240064
# Developed By: K.Madhava Reddy
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by : K.Madhava Reddy
Register Number : 212223240064
'''
import numpy as  np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: K.Madhava Reddy
RegisterNumber: 212223240064
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix.
Developed by : K.Madhava Reddy
RegisterNumber : 212223240064
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Madhavareddy09/Norm-of-a-matrix/assets/145742470/1d35a57d-1244-4e91-8da2-ee80b37798f9)

### 2-Norm of a Matrix
![image](https://github.com/Madhavareddy09/Norm-of-a-matrix/assets/145742470/ec6618fa-792e-41ea-a029-179c7674c791)

### Infinity Norm of a Matrix
![image](https://github.com/Madhavareddy09/Norm-of-a-matrix/assets/145742470/c917ea8b-00b5-4ef0-8fac-ec0ab12d4880)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
