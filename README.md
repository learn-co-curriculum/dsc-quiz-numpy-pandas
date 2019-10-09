# NumPy and Pandas - Quiz

We recommend you **do not** use Python to answer these questions. Instead, based on what you have learned in this section, _reason_ the code to choose an expected answer. 

# Arrays and DataFrames

?: Fill in the blank such that `x` prints the following output:  

```python
import numpy as np
x = ___
print(x)

array([1, 2, 3])
```

( ) `array([1, 2, 3])`
(X) `np.array([1, 2, 3])`
( ) `np.array(1, 2, 3)`
( ) `numpy.array([1, 2, 3])`


?: What is the output of the following code? 


```python
import numpy as np
x = np.array([[1, 2, 3], [4, 5, 6]])
print(x[1, 1])
```

( ) `1` 
( ) `4`
(X) `5`
( ) `[1, 4]`


?: How do you convert the data type of the column `'x'` in `df` from an `object` to an integer? 

( ) `df['x'].astype('integer)`
( ) `int(df['x'])` 
( ) `df['x'].int` 
(X) `df['x'].astype(int)` 


?: As shown below, the indices of `df` are 0 through 3. Which command updates the indices of `df` to `days`?  

```python
df

     x   y
0   22  31
1   45  56
2   10  20
3   30  42

days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday']
```

( ) `df[indices] = days` 
( ) `index(df) = days` 
(X) `df.index = days` 
( ) `df.index(days)`


?: In what order should you run the following commands in order to generate and display a labelled plot? 

1. `plt.title('Example plot')`  
2. `data.plot()`  
3. `plt.show()`  
4. `import matplotlib.pyplot as plt` 


( ) 2-1-3-4
( ) 4-1-2-3
( ) 3-4-2-1
(X) 4-2-1-3



???
