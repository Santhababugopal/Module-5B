#  Pandas Program: Join Two DataFrames Along Rows

##  AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

##  ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

##  Program

```
import pandas as pd
a=eval(input())
b=eval(input())
print("Original DataFrames:")
row=pd.DataFrame(a)
row1=pd.DataFrame(b)
print(row)
print(row1)
print("Merged data (outer join):")
mdf=pd.merge(row,row1,on='s_id',how='outer')
print(mdf)
```

## Output
<img width="1515" height="353" alt="image" src="https://github.com/user-attachments/assets/48312bc1-e896-4498-8651-901fdfe4e720" />

## Result
The program successfully concatenates two DataFrames row-wise using pd.concat() and prints the merged DataFrame.
