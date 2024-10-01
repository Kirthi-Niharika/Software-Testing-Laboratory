# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                       
### REGISTER NUMBER : 212221040084

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

a) do…while
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
         print("Enter a valid positive number.")
display()
```
 b) while…do
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1 
else:
    print("Enter a valid positive number.")

```
 c) if …else 
```
def compare(): 
    a=input("Enter a value for A: ") 
    b=input("Enter a value for B: ") 
    try: 
        a=int(a) 
        b=int(b) 
        if a>b: 
            print("A is greater than B") 
        elif a<b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print('Enter a valid number.') 
compare()
```

  d) switch 
```
def switch(): 
    switcher={ 0:"even", 1:"odd" } 
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2]) 
    except ValueError: 
        print("Enter a valid number.") 
switch() 

```

  e) for 
```
def iterate():
    string=input("Enter a string: ")
    for i in string: 
        print(ord(i),end=" ") 
iterate()

```


### Output:
```
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 2
Enter a positive value for END: 6
2 3 4 5 6 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 6
Enter a positive value for END: 2
6 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 0
Enter a positive value for END: 0
0 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 1
Enter a positive value for END: 10
1 2 3 4 5 6 7 8 9 10 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 0
Enter a positive value for END: 7
0 1 2 3 4 5 6 7 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 7
Enter a positive value for END: 0
7 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: hi
Enter a positive value for END: bye
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: -87
Enter a positive value for END: -9
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: gjkj
Enter a positive value for END: hh
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: ++
Enter a positive value for END: --/
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 2+
Enter a positive value for END: 1
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: A
Enter a positive value for END: Z
Enter a valid positive number.
```
```
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: 2
Enter a positive value for END: 8
2
3
4
5
6
7
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: 7
Enter a positive value for END: 9
7
8
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: 18
Enter a positive value for END: -9
Enter a valid positive number.
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: 8
Enter a positive value for END: 
Enter a valid positive number.
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: 
Enter a positive value for END: 
Enter a valid positive number.
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: Ef
Enter a positive value for END: j
Enter a valid positive number.
========== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =========
Enter a positive value for START: =
Enter a positive value for END: 
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: 
Enter a positive value for END: =
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: +
Enter a positive value for END: 
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: -98
Enter a positive value for END: -98
Enter a valid positive number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: 2
Enter a positive value for END: 2
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: 2
Enter a positive value for END: 0
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1b.py =====
Enter a positive value for START: 7
Enter a positive value for END: 2
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 0
Enter a positive value for END: 0
0 
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 
Enter a positive value for END: 
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 09
Enter a positive value for END: 08
9 
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 02
Enter a positive value for END: 04
2 3 4 
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 0.7
Enter a positive value for END: 8
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: ++
Enter a positive value for END: --\
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: gjkj
Enter a positive value for END: oo
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: -4
Enter a positive value for END: -1
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: -6
Enter a positive value for END: -6
Enter a valid positive number.
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 6
Enter a positive value for END: 6
6 
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 1
Enter a positive value for END: 7
1 2 3 4 5 6 7 
======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for START: 7
Enter a positive value for END: 1
7 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1a.py =====
Enter a positive value for START: 
 ======= RESTART: C:\Users\Kirthi\OneDrive\Desktop\STL exp\stlb.py ======
Enter a positive value for END: Enter a valid positive number.
```
```
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 0
even
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: -878
even
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: -+=
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: A
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: int(a)
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 9
odd
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 123456
even
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 7890
even
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 1357
odd
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 0985
odd
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 000000000000
even
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: DHFJG
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1c.py =====
Enter a value for N: 1
odd
```
```
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 8
Enter a value for B: 3
A is greater than
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 10
Enter a value for B: 6
A is greater than B
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 10000
Enter a value for B: 99999
B is greater than A
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 0.7
Enter a value for B: 6.0
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 9.0
Enter a value for B: 2.0
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 501
Enter a value for B: 501
A is equal to B
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 1234567
Enter a value for B: 1234567
A is equal to B
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 13579
Enter a value for B: 97531
B is greater than A
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 1
Enter a value for B: 1
A is equal to B
0
0
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 0
Enter a value for B: 0
A is equal to B
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: -3
Enter a value for B: 4
B is greater than A
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: 09
Enter a value for B: 08
A is greater than B
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: =-=
Enter a value for B: ++
Enter a valid number.
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1d.py =====
Enter a value for A: A
Enter a value for B: Z
Enter a valid number.
```
```
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: stdfj
115 116 100 102 106 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: A
65 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: Aa
65 97 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 
32 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: /
47 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: ||
124 124 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: Z z A+B
90 32 122 32 65 43 66 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 'hello world!'
39 104 101 108 108 111 32 119 111 114 108 100 33 39 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: {}()[]<>
123 125 40 41 91 93 60 62 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 0.6
48 46 54 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 0
48 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 45
52 53 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: 52 53
53 50 32 53 51 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: `~{
96 126 123 
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/STL exp/stl 1e.py =====
Enter a string: (^~^)
40 94 126 94 41
```

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


