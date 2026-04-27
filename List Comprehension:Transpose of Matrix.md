# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```py

def create(r, c):
    return [[int(input()) for _ in range(c)] for _ in range(r)]

r, c = map(int, input().split())
A = create(r, c)
print([[A[i][j] for i in range(r)] for j in range(c)])
```
## OUTPUT:

<img width="860" height="560" alt="447880004-a68505db-8baf-4c04-af81-79325942afe8" src="https://github.com/user-attachments/assets/89aba5dc-3a5d-4029-af70-ee6ab2dd9a0a" />

## RESULT:
Thus, the program has been executed successfully.

