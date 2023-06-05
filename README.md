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
# Register No:212222230093
# Developed By:Naveen Raja N.R
# 1-Norm of a Matrix

#developer name:Naveen Raja N.R
#register no:212222230093

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Naveen Raja N.R
RegisterNumber: 212222230093
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Naveen Raja N.R
RegisterNumber: 212222230093
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>![Screenshot (63)](https://github.com/naveenraja2004/Norm-of-a-matrix/assets/118707204/837d7c94-74f4-40b1-b799-0a2d72ec05d8)


### 2-Norm of a Matrix
<br>
<br>![Screenshot (62)](https://github.com/naveenraja2004/Norm-of-a-matrix/assets/118707204/a4e79595-5af3-47e2-a37b-85032ccdcc71)

<br>

### Infinity Norm of a Matrix
<br>![Screenshot (61)](https://github.com/naveenraja2004/Norm-of-a-matrix/assets/118707204/b6a702e8-3659-4380-92e8-029e0aa7adcb)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
