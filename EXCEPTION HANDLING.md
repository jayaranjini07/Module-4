# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To Write a python program to raise an user defined exception for the guessing number problem where the user has to guess the number 10.
This program will ask the user to enter a number until they guess a stored number correctly. To help them figure it out, a hint is provided whether their guess is greater than or less than the stored number.

---

### ALGORITHM

1. Start
2. Input an integer and store it in variable a
3. Try Block:
-If a is equal to 10:
 -Print: "Congratulations! You guessed it correctly."
4. Finally Block (executes regardless of the try block result):
-If a is greater than 10:
 -Print: "This value is too large, try again!"
-Else if a is equal to 10:
 -Do nothing (pass)
-Else (i.e., a is less than 10):
 -Print: "This value is too small, try again!"
5. End

---

### PROGRAM

```
Reg.No: 212223060101
Name: JAYA RANJINI S
a=int(input())
try:
    if(a==10):
        print("Congratulations! You guessed it correctly.")
finally:
    if(a>10):
        print("This value is too large, try again!")
    elif(a==10):
        pass
    else:
        print("This value is too small, try again!")

```

### OUTPUT

![image](https://github.com/user-attachments/assets/37115c59-a1db-4642-9c4f-a45206edd88e)

### RESULT
Thus the python program to raise an user defined exception for the guessing number problem where the user has to guess the number 10 was implemented and executed successfully.
