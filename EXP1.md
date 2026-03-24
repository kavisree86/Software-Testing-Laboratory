# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER :212222047011

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
```
a)do...while

def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end='')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()

b)while..do

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

c)if...else

a=int(input("Enter a = "))
b=int(input("Enter b = "))
if a>b:
    print("a is greater than b")
elif a<b:
    print("b is greater than a")
elif a==b:
    print("a is equal to b")
else:
    print("enter a valid input")

d)switch

def switch():
    switcher={
        0:"even",
        1:"odd"
    }
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()

e)for

def iterate():
    string=input("Enter a string: ")
    for i in string:
        print(ord(i),end=" ")
iterate()
```












### Output:

<img width="1035" height="1002" alt="image" src="https://github.com/user-attachments/assets/715fd44c-2d6e-4314-8e81-80bba672d264" />






### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


