# 3-3-MATRIX
import numpy as np
c=np.array([[100,200,300],[400,500,600],[700,800,900]])
print("matrix c\n",c)
trans_matrix=np.transpose(c)
print("the transpose of matrix c is \n",trans_matrix)

 
#b create 3*3 matrix and perform matrix multiplication
d=np.array([[11,22,33],[44,55,66],[77,88,99]])
multiply_arr=np.dot(c,d)
print("matrix multiplication of c and d are\n",multiply_arr)
