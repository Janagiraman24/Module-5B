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

## 💻 Program
```
import pandas as pd
import numpy as np
dic1=eval(input())
dic2=eval(input())
df1=pd.DataFrame(dic1)
df2=pd.DataFrame(dic2)
print("Original DataFrames:")
print(df1)
print(df2)
print("Merged data (inner join):")
res=pd.merge(df1,df2,on='student_id')
print(res)
```

## Output
![image](https://github.com/user-attachments/assets/ff88a996-a463-4521-ab4e-344aa1cf0fe0)

## Result
Thus the program has been successfully executed.
