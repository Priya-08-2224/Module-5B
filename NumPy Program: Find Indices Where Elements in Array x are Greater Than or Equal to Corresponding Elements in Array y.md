# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

```
import numpy as np
x = np.array([10, 20, 30, 40, 50])
y = np.array([15, 10, 25, 35, 45])
indices = np.where(x >= y)[0]  
print("Indices where elements in x are greater than or equal to corresponding elements in y:")
print(indices)

```
## Output
![image](https://github.com/user-attachments/assets/f44255e7-80c9-4ecd-8a78-6bdd265c37c5)

## Result
The program successfully finds and prints the indices where elements of x are greater than or equal to the corresponding elements in y. The result matches the expected output.
