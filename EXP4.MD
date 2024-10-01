# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE:                                                                            
### REGISTER NUMBER : 212221040084
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
x = input("Enter the input: ") 
if x.isnumeric(): 
    x = int(x) 
    temp = x 
    cube = 0; 
    while(temp>0): 
        digit = temp%10 
        cube = cube + (digit**3) 
        temp//=10 
    if(cube == x): 
        print("Armstrong Number") 
    else: 
        print("Not Armstrong Number") 
else: 
    print("Enter a Positive Integer.")
```
### Output:
```
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 876
Not Armstrong Number
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 153
Armstrong Number
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: ,,l
Enter a Positive Integer.
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 5.6
Enter a Positive Integer.
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 
Enter a Positive Integer.
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 000
Armstrong Number
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 0
Armstrong Number
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 111
Not Armstrong Number
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: 321
Not Armstrong Number
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: hi
Enter a Positive Integer.
>>> 
====== RESTART: C:/Users/Kirthi/OneDrive/Desktop/Desktopp/STL exp/stl 4.py =====
Enter the input: -153
Enter a Positive Integer.
```
### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
