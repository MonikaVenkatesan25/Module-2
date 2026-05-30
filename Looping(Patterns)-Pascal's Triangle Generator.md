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
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
for space in range(1, rows-i+1):
 print(" ",end="")
for j in range(0, i):
if j==0 or i==0:
coef = 1
else:
 coef = coef * (i - j)
print(coef, end = " ")
print()

```

## Sample Output
<img width="544" height="618" alt="445699634-0ee73e38-819f-4807-a654-6e77b3570e91" src="https://github.com/user-attachments/assets/241f8143-286d-42ab-8d5a-615c6b2b778d" />


## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.
