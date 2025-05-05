# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr = np.array([[34, 12, 45], [23, 56, 11], [10, 8, 39]])
sorted_arr = np.sort(arr, axis=0)
print("Original Array:")
print(arr)
print("\nColumn-wise Sorted Array:")
print(sorted_arr)

```
## Output
![image](https://github.com/user-attachments/assets/6bcb7d83-20cf-4e81-b7af-4625d85cbd3e)

## Result
The program executed successfully, sorting the elements of the array column-wise in ascending order. The original array and the sorted array were both displayed.
