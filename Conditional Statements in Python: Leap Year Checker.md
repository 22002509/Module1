## Experiment No: 4 – Conditional Statements- Python Leap Year Checker

## AIM  
To write a Python program to compute whether a given year is a leap year or not.
## ALGORITHM  
1.	Get the year from the user as input.
2.	Check if the year is divisible by 4.
3.	If the year is divisible by 4, check if it is also divisible by 100.
4.	If the year is divisible by 100, check if it is divisible by 400.
5.	If the year is divisible by 400, then it is a leap year.
6.	If the year is divisible by 4 but not by 100, then it is a leap year.
7.	Otherwise, it is not a leap year.
8.	Print the result indicating whether the given year is a leap year or not.

## PROGRAM
```python
# Reg.No-212222040120
# Name-PRASANNA R
# Write your code here

yr=int(input())
if yr%100==0:
    if yr%400==0:
        print("Given year",yr,"is a leap year")
    else:
        print("Given year",yr,"is not a leap year")
else:
    if yr%4==0:
        print("Given year",yr,"is a leap year")
    else:
        print("Given year",yr,"is not a leap year")
```

## OUTPUT

![LAB1 DAY4 op](https://github.com/user-attachments/assets/8287f72a-4a42-4ea8-bfd6-7784ba52823a)


## RESULT
Thus, the Python program to compute whether a given year is a leap year or not has been implemented and executed successfully.
