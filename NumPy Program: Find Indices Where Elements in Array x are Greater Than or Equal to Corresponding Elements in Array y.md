
## Aim
Create a numpy program to replace all the elements of the numpy array which are greater than 30 to 0



## Algorithm
```
Step 1: Start the program. 
Step 2: Take the necessary input(s) from the user. 
Step 3: Process the input(s) using suitable operations or conditions. 
Step 4: Display the result/output to the user. Step 5: Stop the program.

```
## Program
```
import numpy as np

# Read input as a list (e.g., [49, 7, 44, 27, 13, 35, 71])
arr = np.array(eval(input()))

# Replace elements > 30 with 0
arr[arr > 30] = 0

# Print the result
print(arr)


```


## Output
<img width="876" height="240" alt="image" src="https://github.com/user-attachments/assets/a5754ae6-0113-4446-94e4-fd1723fe71e8" />

## Result
The Program was ececuted successfully
