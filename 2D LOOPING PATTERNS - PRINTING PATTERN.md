# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

### AIM  
To write a python program to print Pascal triangle

### ALGORITHM

1. Begin the program.
2. Use input() to get the number of rows (rows) from the user.
3. Initialize coef to 1.
4. Use a nested for loop to generate and print Pascal’s Triangle:
   Outer loop for rows from 1 to rows.
   Inner loop for spaces to align the numbers.
   Inner loop for calculating and printing the coefficients.
5. Print the result for each row.
6. Terminate the program.

### PROGRAM
```
#REG NO: 212222220022
#NAME: MANIKANDAN R
rows=int(input())
coef=1
for i in range(1,rows+1):
    for space in range(1,rows-i+1):
        print(" ",end="")
    for j in range(0,i):
        if j==0 or i==0:
            coef=1
        else:
            coef=coef*(i-j)//j
        print(coef,end=" ")
    print()
```

### OUTPUT
![Screenshot 2025-04-27 142321](https://github.com/user-attachments/assets/626fd405-8742-4486-9f8d-84d71346b46b)

### RESULT
Thus a python program to print Pascal triangle has been implemented successfully.
