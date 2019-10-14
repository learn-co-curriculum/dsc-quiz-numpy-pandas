# NumPy and Pandas - Quiz

We recommend you **do not** use Python to answer these questions. Instead, based on what you have learned in this section, _reason_ the code to choose an expected answer. 

???

# Arrays and DataFrames

?: Question 1  


Fill in the blank such that `x` prints the following output:  

```python
import numpy as np
sample_array = ___
print(sample_array)

array([1, 2, 3])
```

( ) `array([1, 2, 3])`
(X) `np.array([1, 2, 3])`
( ) `np.array(1, 2, 3)`
( ) `numpy.array([1, 2, 3])`


?: Question 2   


What is the output of the following code? 


```python
import numpy as np
sample_array = np.array([[1, 2, 3], [4, 5, 6]])
print(sample_array[1, 1])
```

( ) `1` 
( ) `4`
(X) `5`
( ) `[1, 4]`


?: Question 3   


How do you convert the data type of the column `'x'` in `df` from an `object` to an integer? 

( ) `df['x'].astype('integer)`
( ) `int(df['x'])` 
( ) `df['x'].int` 
(X) `df['x'].astype(int)` 


?: Question 4   


As shown below, the indices of `df` are 0 through 2. Which command updates the indices of `df` to `dates`?  

|    |   temperature |   humidity |
|----|---------------|------------|
|  0 |            70 |         85 |
|  1 |            68 |         80 |
|  2 |            71 |         80 |

```python
dates = ['2018/01/01', '2018/01/02', '2018/01/03']
```

( ) `df[indices] = dates` 
( ) `index(df) = dates` 
(X) `df.index = dates` 
( ) `df.index(dates)`


?: Question 5    


In what order should you run the following commands in order to generate and display a labelled plot? 

1. `plt.title('Example plot')`  
2. `data.plot()`  
3. `plt.show()`  
4. `import matplotlib.pyplot as plt` 


( ) 2-1-3-4
( ) 4-1-2-3
( ) 3-4-2-1
(X) 4-2-1-3



???
