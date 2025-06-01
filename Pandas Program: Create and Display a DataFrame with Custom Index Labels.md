# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`
2. **Index Labels**: Create a list of custom index labels called `labels`.
3. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
4. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
d=dict(eval(input()))
df=pd.DataFrame(d)
print(df)
```

## Output
![image](https://github.com/user-attachments/assets/1e0ff49e-8d2a-4260-b27b-f35d71e12e33)

## Result
Thus the program has been successfully executed.
