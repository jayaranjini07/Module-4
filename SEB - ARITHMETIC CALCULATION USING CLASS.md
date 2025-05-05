# Exp.No:20  
## SEB - CLASS AND METHODS

---

### AIM  
To write a Python class which has two methods get_String and print_String. get_String accept a string from the user and print_String print the string in upper case.

---

### ALGORITHM

Sure! Here's a **short version of the algorithm**:

---

### **Algorithm (Short Version):**

1. Define class `c` with:
   * Variable `a` initialized as an empty string.
   * Method `get_String` to take user input and store in `a`.
   * Method `print_String` to print `a` in uppercase.
2. Create object `c1` of class `c`.
3. Call `c1.get_String()` to get input.
4. Call `c1.print_String()` to display the input in uppercase.

---

### PROGRAM

```
class c:
    def __init__(self):
        self.a=""
    def get_String(self):
        self.a=input()
    def print_String(self):
        print(self.a.upper())
c1=c()
c1.get_String()
c1.print_String()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/bbb3962f-ebe5-4c46-b299-3d508cafe198)

### RESULT
Thus the Python class which has two methods get_String and print_String. get_String accept a string from the user and print_String print the string in upper case was implemented and executed successfully.
