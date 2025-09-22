# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING NATURAL NUMBERS

###  Aim
Python Program to print numbers range from M to N (including M and N values)

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```
# Function to print numbers from M to N
def print_range(M, N):
    for number in range(M, N + 1):
        print(number)

# Taking input from the user
M = int(input())
N = int(input())

# Printing the range
print_range(M, N)

```
### OUTPUT


10
11
12
13
14
15


### RESULT

<img width="355" height="595" alt="image" src="https://github.com/user-attachments/assets/50ca1b2f-22fa-46d6-b874-50ea8afebaaa" />


