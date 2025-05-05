# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```
import pandas as pd
student_data1 = {
    'name': ['Alice', 'Bob', 'Charlie'],
    'age': [20, 21, 19],
    'score': [85, 92, 88]
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'name': ['David', 'Eva'],
    'age': [22, 20],
    'score': [95, 78]
}
df2 = pd.DataFrame(student_data2)
df_combined = pd.concat([df1, df2], axis=0, ignore_index=True)
print(df_combined)
```
## Output
![image](https://github.com/user-attachments/assets/51314fad-f8c7-431d-afd0-e06cf0442f27)

## Result
The program successfully combines the two DataFrames row-wise and displays the result.

