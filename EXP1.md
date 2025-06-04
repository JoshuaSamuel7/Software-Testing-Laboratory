# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

## DATE:  13.03.25                                                                       
## REGISTER NUMBER : 212222040065

## AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

## ALGORITHM:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
## PROGRAM:
### do...while:
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start=int(start) 
            end=int(end) 
            print(start,end=" ") 
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display() 
```
### while...do:
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
### switch:
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
### if..else:
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
        print("Enter a valid number.")

compare()
```
### for:
```
def iterate(): 
    string=input("Enter a string: ") 
    for i in string: 
        print(ord(i),end=" ") 
iterate()
```
## OUTPUT:
![exp1a(1)](https://github.com/user-attachments/assets/f1b08ae2-315a-47dd-9737-797b62580bdf),![exp1a(2)](https://github.com/user-attachments/assets/7bb2e390-8659-47cf-918f-bd019b99045d)

![exp1b(1)](https://github.com/user-attachments/assets/21e1f8d7-1603-4322-8a65-098da7099358),![exp1b(2)](https://github.com/user-attachments/assets/613c350a-cac8-42c5-8a49-41b293166782)

![exp1c](https://github.com/user-attachments/assets/0e0682d9-f9d4-42d4-9ef4-bac976619a83)

![exp1d](https://github.com/user-attachments/assets/12e17f39-c23f-41e1-a4ee-fa5bfcfec4c4)

![exp1e](https://github.com/user-attachments/assets/c72e528d-fe8b-4801-8ffa-dc8baa6b3b42)

## RESULT:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
