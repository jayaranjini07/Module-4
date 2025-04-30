# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula. 
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
class umbrella:
    def _init_(self,radius):
        self.radius=radius
    def rain(self):
        area=3.141592*radius*radius
        return area
u=umbrella()
radius=int(input())
print("Area of circle: {:.2f}".format(u.rain()))

```

### OUTPUT

![image](https://github.com/user-attachments/assets/995058ee-da84-4460-98cc-6bd6d570673a)

### RESULT
Thus the Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain` was implemented and executed successfully.



