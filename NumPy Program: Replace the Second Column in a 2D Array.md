# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
arr=np.array(eval(input()))
col=np.array(eval(input()))
print("Before inserting new row")
print("",arr)
print("After inserting new row")
arr=np.insert(arr,3,col,axis=0)
print("",arr)
```

## Output
![image](https://github.com/user-attachments/assets/e513309c-323a-4f6f-98e6-e625a245862f)

## Result
Thus the program has been successfully executed.
