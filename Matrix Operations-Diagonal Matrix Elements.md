# Matrix Operations-Diagonal Matrix Elements Printer 🧮

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

## 📌 Aim

To write a Python program that prints only the diagonal elements of a given matrix.

## 🧠 Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

## 🖥️ Program
```py

r, c = int(input()), int(input())
m = [list(map(int, input().split())) for _ in range(r)]
print(m)
for i in range(r):
    print(' '.join(str(m[i][j]) if i == j else ' ' for j in range(c)))
```
### Output:

<img width="815" height="363" alt="447881695-1ed1d500-87c2-41f9-afb2-f81c7e793be6" src="https://github.com/user-attachments/assets/c2bda4ff-4daf-44c3-b004-3a584e0ccd89" />

## Result
Thus, the program has been executed successfully.
