# Ex.No: 2   Matrix Multiplication 

### DATE:                                                                            
### REGISTER NUMBER : 212221040084

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:
```
r1, c1 = input("enter row and column count in matrix 1: ").split()
r2, c2 = input("enter row and column count in matrix 2: ").split()
matrix1 = []
matrix2 = []
result = []
if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1 = int(r1)
    r2 = int(r2)
    c1 = int(c1)
    c2 = int(c2)
    if c1 != r2:
        print("Matrix multiplication not possible")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible")
    else:
        for i in range(r1):
            a = []
            for j in range(c1):
                a.append(int(input("<-")))
            matrix1.append(a)
        
        for i in range(r2):
            a = []
            for j in range(c2):
                a.append(int(input("<-")))
            matrix2.append(a)
        
        for i in range(r1):
            inter = []
            for j in range(c2):
                sum = 0
                for k in range(c1):  
                    sum += matrix1[i][k] * matrix2[k][j]
                inter.append(sum)
            result.append(inter)
        
        for i in range(r1):
            for j in range(c2):
                print(result[i][j], end=" ")
            print()
else:
    print("enter a valid number")
```
### Output:
```
= RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py
enter row and column count in matrix 1: 2 3
enter row and column count in matrix 2: 2 3
Matrix multiplication not possible
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 0 0
enter row and column count in matrix 2: 0 0
Matrix multiplication not possible
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 2 3
enter row and column count in matrix 2: 3 1
<-1
<-2
<-3
<-4
<-5
<-6
<-7
<-1
<-0
9 
33 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 1 2
enter row and column count in matrix 2: 2 1
<-1
<-2
<-2
<-1
4 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: -9 -5
enter row and column count in matrix 2: 0 7
enter a valid number
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: -5 -2
enter row and column count in matrix 2: -2 3
enter a valid number
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 123 123
enter row and column count in matrix 2: 123 234
Matrix multiplication not possible
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 1 1
enter row and column count in matrix 2: 1 2
<-1
<-2
<-1
2 1 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 1 1
enter row and column count in matrix 2: 1 2
<-1
<-1
<-2
1 2 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 1 1
enter row and column count in matrix 2: 2 1
Matrix multiplication not possible
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 2 3
enter row and column count in matrix 2: 3 2
<-1
<-2
<-1
<-0
<-1
<-0
<-1
<-1
<-`
Traceback (most recent call last):
 File "C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py", line 27, in 
<module>
 a.append(int(input("<-")))
ValueError: invalid literal for int() with base 10: '`'
>>> 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 1 2
enter row and column count in matrix 2: 2 3
<-1
<-1
<-0
<-2
<-1
<-6
<-1
<-0
6 3 1 
>>> 
====== RESTART: C:\Users\Kirthi\OneDrive\Desktop\Desktopp\STL exp\stl 2.py =====
enter row and column count in matrix 1: 2 2
enter row and column count in matrix 2: 2 2
<-1
<-0
<-1
<-2
<-3
<-2
<-0
<-2
3 2 
3 6
```
### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.
