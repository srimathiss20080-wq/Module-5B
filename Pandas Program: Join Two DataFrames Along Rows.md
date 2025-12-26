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

student_data1 = { 'student_id': ['S1', 'S2', 'S3', 'S4'], 'name': ['Alice', 'Bob', 'Charlie', 'David'], 'marks': [85, 90, 95, 80] }

student_data2 = { 'student_id': ['S5', 'S6'], 'name': ['Eva', 'Frank'], 'marks': [88, 92] }

df1 = pd.DataFrame(student_data1) 
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0)

print(combined_df)
```
## Output
<img width="1647" height="657" alt="image" src="https://github.com/user-attachments/assets/afbf8098-415b-4dcb-8501-8dcccb043d5f" />

## Result
Thus To write a Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame. Hence the code has been executed successfully.

