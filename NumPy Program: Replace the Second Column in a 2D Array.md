# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np
original_array = np.array([[10, 20, 30], [40, 50, 60], [70, 80, 90]])
new_column = np.array([100, 200, 300])  
updated_array = np.delete(original_array, 1, axis=1)
updated_array = np.insert(updated_array, 1, new_column, axis=1)
print("Original Array:")
print(original_array)
print("\nUpdated Array with New Column:")
print(updated_array)
```
## Output
![image](https://github.com/user-attachments/assets/35850779-f086-414c-9b19-c559d83ef7c4)

## Result
The program successfully deletes the second column and inserts the new column at the same position in the updated array. It prints both the original and updated arrays as expected.
