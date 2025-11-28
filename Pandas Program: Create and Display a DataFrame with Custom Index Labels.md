5D: Pandas Program: Create and Display a DataFrame with Custom Index Labels

##  Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.



##  Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.



##  Program
```
import pandas as pd
import numpy as np

data=eval(input())
new=eval(input())

df=pd.DataFrame(data)
df.index=new
print(df)

```

## Output
<img width="1190" height="141" alt="image" src="https://github.com/user-attachments/assets/45257714-6fab-470e-9677-69e2081b6a60" />

## Result
Thus, the Pandas program successfully creates a DataFrame from a dictionary and assigns user-defined custom index labels to the rows.
