# NumPy Program: Replace the Second Column in a 2D Array

##  Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

##  Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

##  Program

```
import numpy as np

a=eval(input())
b=eval(input())

print("Printing Original array")
arr1=np.array(a)
new=np.array(b)
print(arr1)
print("Array after deleting column 2 on axis 1")
del_arr1=np.delete(arr1,1,axis=1)
print(del_arr1)
print("Array after inserting column 2 on axis 1")
ins_arr=np.insert(del_arr1,1,new,axis=1)
print(ins_arr)
```

## Output
<img width="1130" height="731" alt="image" src="https://github.com/user-attachments/assets/bae45cc7-98eb-49b2-9639-eaf95939e23b" />

## Result
Thus, the NumPy program successfully deletes the second column from the original 2D array and inserts a new column at the same position.
