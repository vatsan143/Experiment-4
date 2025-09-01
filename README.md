# Experiment-4

## ARMSTRONG NUMBER 
## Aim:  Write a python program to check the number is Armstrong number or not and inspect for failures. 

## Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

## Program
#### NAME: SRIVATSAN G
#### REG NO: 212223230216
```
x = input("Enter a number: ")  
if x.isnumeric():  
    x = int(x)  
    temp = x  
    cube = 0  
    while temp > 0:  
        digit = temp % 10  
        cube += digit ** 3  
        temp //= 10  
    if cube == x:  
        print("Armstrong Number")  
    else:  
        print("Not an Armstrong Number")  
else:  
    print("Enter a Positive Integer.")

```
## Output
<img width="656" height="249" alt="image" src="https://github.com/user-attachments/assets/40e068b4-f63d-43ec-a89f-f280b19b0257" />

## Result
Thus, the python program to check the number is Armstrong number or not and inspect for failures is executed successfully.
