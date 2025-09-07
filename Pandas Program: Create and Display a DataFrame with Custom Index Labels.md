
## Aim
Create a Pandas program to join the two given dataframes along rows and assign all data.



## Algorithm
```
Step 1: Start the program. 
Step 2: Take the necessary input(s) from the user. 
Step 3: Process the input(s) using suitable operations or conditions. 
Step 4: Display the result/output to the user. Step 5: Stop the program.

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
