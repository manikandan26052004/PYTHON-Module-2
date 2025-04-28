# Exp.No:2e  
  ## SEB - SUM OF THE SERIES

### AIM  
To Write a Python Program to find the sum of series 1+3+5+7.......+N 

### ALGORITHM

1. Begin the program.
2. Use input() to get the value of a from the user.
3. Initialize sum to 0.
4. Use a for loop to iterate from 1 to a: Check if the current number i is odd (i.e., i % 2 != 0).If true, add i to sum.
5. Print the sum of the series.
6. Terminate the program.

### PROGRAM
```
#REG NO: 212222220022
#NAME: MANIKANDAN R
a=int(input())
sum=0
for i in range (1,a+1):
    if i%2!=0:
        sum+=i
print(f"The sum of the series =  {sum}")
```
### OUTPUT
![Screenshot 2025-04-27 143122](https://github.com/user-attachments/assets/71b9f81f-6487-4ed7-a679-7deda1dee7a5)

### RESULT
Thus a Python Program to find the sum of series 1+3+5+7.......+N has been successfully implemented.
 
