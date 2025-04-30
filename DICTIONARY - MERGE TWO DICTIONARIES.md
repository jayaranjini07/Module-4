# Exp.No:16  
## DICTIONARY - MERGE TWO DICTIONARIES

---

### AIM  
To Merge the two python dictionaries into one
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

---

### ALGORITHM

1. Start
2. Create dict1 with key-value pairs: 'Ten': 10, 'Twenty': 20, 'Thirty': 30.
3. Create dict2 with key-value pairs: 'Thirty': 30, 'Fourty': 40, 'Fifty': 50.
4. Use dict1.update(dict2) to:
-Add all key-value pairs from dict2 into dict1.
-If a key from dict2 already exists in dict1 (like 'Thirty'), its value will be overwritten.
5. Assign dict1 to dict3 (both will now point to the same dictionary object).
6. Print dict3.
7. End

---

### PROGRAM

```
#Reg.No:212223060101
#Name:JAYA RANJINI S

dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}
dict1.update(dict2)
dict3 = dict1
print(dict3)


```

### OUTPUT

![image](https://github.com/user-attachments/assets/842d6b0f-8493-4078-980a-861235726592)

### RESULT
Thus the python program to merge two dictionaries was implemented and executed successfully.
