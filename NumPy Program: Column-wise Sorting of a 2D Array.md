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

x = np.array([1, 3, 5, 7])
y = np.array([2, 3, 4, 8])

indices = np.where(x >= y)

print(indices)
```

## Output
<img width="321" height="151" alt="image" src="https://github.com/user-attachments/assets/f21f5c90-2a26-4b6c-ae87-ee7bdef71f58" />

## Result
Thus code run successfully!

