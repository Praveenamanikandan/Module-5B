
## Aim
Write a numpy program to replace all odd numbers in the given array with -1


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
arr = np.array(eval(input()))
arr[arr % 2 != 0] = -1
print(arr)
```


## Output
<img width="1089" height="227" alt="image" src="https://github.com/user-attachments/assets/24ff053a-f79f-44bd-9449-7bd26764fe1b" />

## Result
The Program was ececuted successfully
