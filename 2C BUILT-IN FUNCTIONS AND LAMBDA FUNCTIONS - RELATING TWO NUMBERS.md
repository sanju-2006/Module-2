# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
Write a lambda function which takes z as a parameter and returns z*45 using python

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
# Define the lambda function
multiply_by_45 = lambda z: z * 45

# Example usage
result = multiply_by_45(int(input()))  # Example input
print(result)  # Output will be 450
```

### OUTPUT

225


### RESULT


<img width="334" height="200" alt="image" src="https://github.com/user-attachments/assets/148cc6c6-ac86-4e9f-a864-735cfe292b54" />


