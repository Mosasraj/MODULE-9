# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
class evennumber:
    def __init__(self,start=200,end=300):
        self.start=start
        self.end=end
        self.ans=self.generate()
    def generate(self):
        return [num for num in range(self.start,self.end+1) if num%2==0]
    def display(self):
        print(self.ans)
a=evennumber()
a.display()
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/b1032baf-5c52-4503-b7ed-fe8a7051bdcb)

## RESULT:
```
Thus the program verified successfully
```
