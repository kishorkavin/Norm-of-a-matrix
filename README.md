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
# Register No:212224230132
# Developed By:Kishore Kavin S
# 1-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)



# 2-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)



# Infinity Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)

```

## Output:
### 1-Norm of a Matrix

![Screenshot 2025-04-21 013902](https://github.com/user-attachments/assets/b547b087-47ec-40ac-bc38-4c16e68e1af1)


### 2-Norm of a Matrix

![Screenshot 2025-04-21 013920](https://github.com/user-attachments/assets/d8f1b48c-f614-41d3-952e-a960efce781c)

### Infinity Norm of a Matrix

![Screenshot 2025-04-21 013935](https://github.com/user-attachments/assets/50f0ddd1-130e-4517-834f-c51bae48877d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
