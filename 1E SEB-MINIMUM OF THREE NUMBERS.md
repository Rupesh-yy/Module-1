# Experiment No: 5 – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the largest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the maximum.  
   - Else, if `num2` is greater than or equal to both `num1` and `num3`, then `num2` is the maximum.  
   - Otherwise, `num3` is the maximum.  
4. Print the maximum value along with the input numbers in the format:  
   `"The maximum of num1, num2, num3 is max."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212222060204
# Name-RUPESH J
# Write your code here

a=int(input())
b=int(input())
c=int(input())
max=(a if(a>b and a>c) else b if (b>a and b>c) else c)
print("The maximum of {}, {}, {} is {}".format(a,b,c,max))
```

## OUTPUT

![lab1 sebexam pdf](https://github.com/user-attachments/assets/86f78d2c-e7c7-4e3d-b8bb-2e1c2a9f1c3f)


## RESULT
Thus, the implementation of Python programming for maximum of three variables verified successfully.
