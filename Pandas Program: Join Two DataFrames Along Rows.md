
##  AIM


To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.



## Algorithm
```
1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

```
## Program
```
import pandas as pd

# Get user input for two dictionaries
data1 = eval(input())
data2 = eval(input())

# Create DataFrames
df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)

# Print original DataFrames
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)

# Join the two DataFrames along rows
result = pd.concat([df1, df2])

# Display the result
print("\nJoin the said two dataframes along rows:")
print(result)

```


## Output
<img width="1220" height="744" alt="image" src="https://github.com/user-attachments/assets/4c6fd73e-b705-4352-8ff6-b8511779c57d" />

## Result
The Program was ececuted successfully
