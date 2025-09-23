# Exp.No:2b  
## FUNCTIONS - SQUARE NUMBER

### AIM  
Write a Python function to create and print a list where the values are square of numbers between 1 and 30 (both included).

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
def printValues(num):
	x=[]
	for i in range(1,num+1):
	    l=i**2
	    x.append(l)
	print(x)

num=20		
printValues(num)

```
### OUTPUT

<img width="1128" height="141" alt="image" src="https://github.com/user-attachments/assets/0776947d-27af-4363-b907-266f99446824" />


### RESULT

Python function to create and print a list where the values are square of numbers between 1 and 30 (both included) is successfully verified
