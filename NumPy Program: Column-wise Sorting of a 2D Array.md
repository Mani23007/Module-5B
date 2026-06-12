# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program:
```python
import numpy as np

a = np.array([[9, 4, 7],[2, 8, 1],[5, 3, 6]])

b = np.sort(a, axis=0)

print("Original Array:")
print(a)

print("Column-wise Sorted Array:")
print(b)
```

## Output:
<img width="386" height="305" alt="image" src="https://github.com/user-attachments/assets/7e532704-ae02-4e0e-b756-f0207c41fea0" />


## Result:
Thus,the program is executed successfully.
