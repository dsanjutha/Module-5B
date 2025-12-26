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
arr = np.array([[9, 2, 7],
                [4, 5, 6],
                [1, 8, 3]])

print("Original Array:")
print(arr)
sorted_arr = np.sort(arr, axis=0)
print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="1144" height="323" alt="Screenshot 2025-12-26 191903" src="https://github.com/user-attachments/assets/471c222a-f393-481b-9407-fb8d357df0d8" />

## Result
The code is executed successfully.
