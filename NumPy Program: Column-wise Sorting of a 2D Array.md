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

array = np.array([[7, 67, 87],
                [43, 54, 98],
                [78, 8, 9]])

sorted_array = np.sort(array, axis=0)

print("Original array:\n", array)
print("Column-wise sorted array:\n", sorted_array)
```
## Output
<img width="1800" height="1020" alt="image" src="https://github.com/user-attachments/assets/5ba139ea-c1e4-4b45-b207-b8397947348f" />


## Result
