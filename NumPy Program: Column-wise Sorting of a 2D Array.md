# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm
1.**Import NumPy:** Start by importing the NumPy library using import numpy as np.
2.**Get Input:** Accept a 2D list input from the user using eval(input()) and convert it to a NumPy array using np.array().
3.**Display Original Array:** Print the original array using print().
4.**Reverse Rows:** Use np.flipud() to reverse the order of the rows in the array (flip up-down).
5.**Store Result:** Store the reversed array in a new variable.
6.**Display Output:** Print the reversed array using print().
## 🧾 Program
```
#Complete the following code
import numpy as np
array = np.array(eval(input()))
print('the given array','\n',array)
reversedArray = np.flipud(array)
print('Reversed array','\n',reversedArray)
```
## Output
![image](https://github.com/user-attachments/assets/9cff9eae-8cc6-477c-85e7-b421df21a8f9)

## Result
Thus the program has been successfully executed.
