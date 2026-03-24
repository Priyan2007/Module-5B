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
Add code here
```
import numpy as np

# Input 2D array
arr = np.array([[3, 1, 2],
                [6, 4, 5],
                [9, 7, 8]])

print("Original Array:\n", arr)

# Sort column-wise
sorted_arr = np.sort(arr, axis=0)

print("Column-wise Sorted Array:\n", sorted_arr)
```
## Output
<img width="402" height="361" alt="image" src="https://github.com/user-attachments/assets/4875df13-4ad3-4d5f-b3fa-d1bbbf6a0c39" />

## Result
Thus the code run successfully!
