A=[]
m=int(input('enter number of row:'))
n=int(input('enter number of columns:'))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row) #[[1 2 3]]
print(A)
B=[]
m=int(input('enter number of row:'))
n=int(input('enter number of columns:'))
for i in range(m):
    raw=[]
    for j in range(n):
        k=int(input())
        row.append(k)
        B.append(row) #[[1 2 3]]
result=[[0,0],[0,0]]
C=[]
for i in range(m):
    for j in range(n):
        result[i][j]=C[i][j]+A[i][j]*B[i][j]
print('resultant matrix is:')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
print()
