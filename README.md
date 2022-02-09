# Inverse-of-matrix

## AIM:

## ALGORITHM:
### Step 1:
Use import as np.
### Step 2:
Enter the input.

### Step 3:
Use for loop and range.

### Step 4:
Use np.linalg.inv() to find inverse of a matrix.

### Step 5:
print()



## PROGRAM:
```py
## DEVELOPED BY: NIVETHA.M
## REGISTER NUMBER:212221240034

import numpy as np
l1, l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
         num=int(input())
         l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1 = np.array(l2)
inverse= np.linalg.inv(value1)
print(inverse)

```

## OUTPUT:
![GitHub Logo](.//i1.png)

## RESULT:
thus the program is written to find the matrix.

