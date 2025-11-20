# NumPy Program: Column-wise Sorting of a 2D Array

##  Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

##  Program
```
import numpy as np

arr = eval(input())
arr = np.array(arr)

print("Printing Original array")
print(arr)

sorted_by_second_row = arr[:, arr[1].argsort()]
print("Sorting Original array by second row")
print(sorted_by_second_row)

sorted_by_second_col = arr[arr[:, 1].argsort()]
print("Sorting Original array by second column")
print(sorted_by_second_col)

```

## Output
<img width="1126" height="729" alt="image" src="https://github.com/user-attachments/assets/88ae9880-6858-4b8c-a903-4e94cd25dfe9" />

## Result
Thus, the program successfully sorts each column of the given 2D NumPy array in ascending order.
