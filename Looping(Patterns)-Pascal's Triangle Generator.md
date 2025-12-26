# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
Add Code Here
```py
def pas(n):
    for i in range(n):
        print(" "*(n-1-i),end="")
        a=1
        for j in range(i+1):
            print(a,end=" ")
            a=a*(i-j)//(j+1)
        print()
n=int(input())
pas(n)
```
## Sample Output
<img width="1148" height="581" alt="image" src="https://github.com/user-attachments/assets/695acb06-c270-41f3-a010-365f510b2c38" />

## Result

