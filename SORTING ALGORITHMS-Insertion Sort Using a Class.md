# 🧮 SORTING ALGORITHMS: Insertion Sort Using a Class

This program demonstrates how to implement the **Insertion Sort algorithm** using a Python class. It allows the user to input a list of numbers, sorts them using the insertion sort technique, and displays the sorted list.

---

## 🎯 Aim

To develop a Python class with functions to:
- Create a list of integers
- Sort it using the **Insertion Sort** algorithm
- Display the sorted list

---

## 🧠 Algorithm

1. **Start the program**
2. **Define a class** `InsertionSorter`
3. Inside the class:
   - `create_list()`:
     - Read number of elements
     - Store them in a list
   - `insertion_sort()`:
     - Iterate from the second element to the end
     - Move elements greater than the key to one position ahead
     - Insert the key at the correct position
   - `print_list()`:
     - Print the sorted list
4. **Create an object** of the class
5. **Call** the methods in order: `create_list()`, `insertion_sort()`, and `print_list()`
6. **End the program**

---

## 💻 PROGRAM:
```
def create_matrix(n,m):
    M=[]
    for i in range(n):
        row=[]
        for j in range(m):
            x=int(input())
            row.append(x)
        M.append(row)
    return M 
def print_matrix(M):
    for i in range(len(M)):
        for j in range(len(M[0])):
            print(M[i][j],end=' ')
        print()
def sort_rows(M):
    S=[]
    for i in M:
        row=sorted(i)
        S.append(row)
    return S
r,c=input().split()
A=create_matrix(int(r),int(c))
print_matrix(A)
print("Resultant Matrix:")
print_matrix(sort_rows(A))
```  
## OUTPUT:

![image](https://github.com/user-attachments/assets/2909bc52-b894-498b-aaf1-b4cb8f5c8110)

## RESULT:
```
Thus ,the program verified successfully
```
