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
# Register No:24010047
# Developed By:RANJITH J
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-12 095136](https://github.com/user-attachments/assets/087ddf24-a693-43be-bc02-361f3e8275db)

### 2-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-12 100421](https://github.com/user-attachments/assets/1bd7f9f3-c4fd-4632-b1ed-46a00363bf5f)

### Infinity Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-12 100527](https://github.com/user-attachments/assets/9e52781b-0bd1-495e-a5b6-f658bb3adebd)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
