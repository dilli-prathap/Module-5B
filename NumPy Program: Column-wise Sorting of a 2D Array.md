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
```PYTHON
import numpy as np 
a=np.array(eval(input())) 
print("Given array") 
print(end=" ") 
print(a) 
print() 
print(np.sort(a,axis=0))
```
## Output
<img width="609" height="256" alt="439334920-cbf933a2-1073-44dc-98c5-e4144d630fe3" src="https://github.com/user-attachments/assets/f875614a-9ada-4c7e-9ee9-5e7da4224a12" />

## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.
