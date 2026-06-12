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

## 💻 Program:
```python
import pandas as pd

student_data1 = {
    'Name': ['Alex', 'Amy', 'Allen'],
    'Marks': [85, 90, 78]
}

student_data2 = {
    'Name': ['John', 'Sara', 'Tom'],
    'Marks': [88, 76, 92]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

new_df = pd.concat([df1, df2], axis=0)

print(new_df)
```

## Output:
<img width="385" height="263" alt="image" src="https://github.com/user-attachments/assets/a0391a2d-1d4a-45f4-9977-cb190abfeb46" />


## Result:
Thus,the program is excuted successfully.
