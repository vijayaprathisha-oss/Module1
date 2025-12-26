# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
a=int(input())
if(a%2!=0):
    print(a,"is an Odd number")
    if(a<25):
        print(a,"is lesser than 25")
    else:
        print(a,"is greater than or equal to 25")
else:
    print(a,"is NOT an Odd number")

## Output
<img width="1017" height="843" alt="1" src="https://github.com/user-attachments/assets/da77d828-78e7-49b9-9c88-6741689d70df" />


## Result
Thus,the given Python Program has been executed successfully.
