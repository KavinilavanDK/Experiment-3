# Experiment-3
## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
Name: KAVI NILAVAN DK

Register Number: 212223230103
```
def is_prime(a,b=None):
    if a<=1:
        return False
    if b==None:
        b=a-1
    if b==1:
        return True 
    if a%b==0:
        return False
    return  is_prime(a,b-1)
a=int(input("Enter the number:"))
try:
    if is_prime:
        print("The given number is prime number")
    else:
        print("The given number is not prime")
except ValueError:
    print("Value Error")

```

## Output
<img width="1445" height="880" alt="image" src="https://github.com/user-attachments/assets/e1823839-2edf-4960-bd6e-ed81bc45339e" />


## Result
Thus, the python program to check the number is prime or not and inspect for failures. 
