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

![image](https://github.com/user-attachments/assets/cea35a7e-4447-46b8-a512-5e8d8f8605ce)
![image](https://github.com/user-attachments/assets/12d15ab8-0ef3-4bca-b359-b9620484a5cf)

![image](https://github.com/user-attachments/assets/da2a60d1-04bc-4205-b199-a49f7a357cb5)
![image](https://github.com/user-attachments/assets/ed205e2c-5cea-47a7-b014-ba3840b3e2cf)

![image](https://github.com/user-attachments/assets/20fd7115-0766-4343-8d2e-f23caa0cce74)
![image](https://github.com/user-attachments/assets/8a3675bc-36b0-4734-b973-592bb4cbd078)

![image](https://github.com/user-attachments/assets/27becebc-3cf3-410e-b178-ce487eff1bae)
![image](https://github.com/user-attachments/assets/5457b600-8990-41cb-ace5-c2c3b404961e)

![image](https://github.com/user-attachments/assets/2b50825f-b489-4243-9876-e4445445f9c8)
![image](https://github.com/user-attachments/assets/f5db8961-b237-4512-9f71-d44d796eced3)
### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
