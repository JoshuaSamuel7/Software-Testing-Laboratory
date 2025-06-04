# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

## DATE: 15.05.2025                                                                        
## REGISTER NUMBER : 212222040065
## AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
## ALGORITHM:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
## PROGRAM:

```
def Palindrome(string):
    for i in range(0, int(len(string)/2)): 
        if(string[i] != string[len(string)-i-1]): 
            return False 
    return True 

s = input("Enter a string: ") 

c = 1 
for i in s: 
    if not(i.isalpha()): 
        c = 0 
        break # Added to stop checking once an invalid character is found

if(c == 0): 
    print("Enter a valid string") 
else:
    answer = Palindrome(s)
    if(answer == True): 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome")
```

## OUTPUT:

![exp6 output](https://github.com/user-attachments/assets/4d055ed1-1404-42d9-8e98-97e4488aa16e)


## RESULT:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
