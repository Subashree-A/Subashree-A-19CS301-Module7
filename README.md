# Subashree-A-19CS301-Module7

- **Name:** Subashree A  
- **Register Number:** 212222020029


# 19CS301-Module7
EX: 7.1 RECURSION
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. STEP 6: Stop.

### Program:
```
def sum_digit(n):
       if n<=0:
            return 0
       else:
            return n%10+sum_digit(n//10)
n = int(input())
sum = sum_digit(n)
print(sum)
```
### Output:
![image](https://github.com/user-attachments/assets/50acc657-266e-46e6-ab17-10358494e26c)

### Result: Thus, the given program is implemented and executed successfully .



 

EX: 7.2 TYPES OF RECURSIONS
### Aim: To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a recursive case in the first line of function for head recursion.

STEP 4: Print the result.

STEP 5: Stop.
### Program:
```
def fun(n):
     if (n >0):
          fun(n - 2)
      print(n-1, end=" ")
x = int(input())
if(x%2==0):
     fun(x)
else:
     fun(x+1)

```
### Output:
![image](https://github.com/user-attachments/assets/c4d6416f-d333-49c1-9dd5-0f774cdabb03)

###Result: Thus, the given program is implemented and executed successfully.
 


EX: 7.3 TAYLOR SERIES

###Aim: To python program to evaluate the series using recursion by collecting the x and n values from the user.
### ALGORITHM:
STEP 1: Start.

STEP 2: Create a variable x and n.

STEP 3: Get the values of x and n from user.

STEP 4: Create a base case and recursive case to calculate the result.

STEP 5: Print the result.

STEP 6: Stop.
### Program:
```
def series(x,n):
         if n==0:
            return 1
         else:
            return x**n/n+series(x,n-1)
x = int(input())
n = int(input())
print(series(x,n))
```
### Output:
![image](https://github.com/user-attachments/assets/1d00b1a4-cecb-466f-8593-805f00d27461)

 
### Result: Thus, the given program is implemented and executed successfully .


 

EX: 7.4 Solve by recursion relation

### Aim: To Write a Python Program to find whether a string is a palindrome or not using recursion

### Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case and recursive case to calculate the result.

STEP 4: Create a variable and get input from user.

STEP 5 : Call the function.

STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
def is_palindrome(word):
      if len(word)<1:
            return True
      else:
            if word[0]==word[-1]:
                 return is_palindrome(word[1:-1])
             else:
                  return False
word = str(input())
if is_palindrome(word)==True:
        print("String is a palindrome")
else:
        print("String is not a palindrome")
```
### Output:
![image](https://github.com/user-attachments/assets/d30ef836-1901-448a-a146-dc905fdc3198)

### Result: Thus, the given program is implemented and executed successfully .

# Ex No 7.5: SEB - Factorial
### Aim:
To write a Python program to calculate the difference between the factorials of two numbers using recursion.

### Algorithm:

**STEP 1:** Start.  
**STEP 2:** Define a recursive function `fact(num)`:
- If `num <= 0`, return 1.
- Else, return `num * fact(num - 1)`.  
**STEP 3:** Accept two integer inputs `a` and `b` from the user.  
**STEP 4:** Call the `fact()` function on both `a` and `b`.  
**STEP 5:** Print the result of `fact(a) - fact(b)`.  
**STEP 6:** Stop.

### Program:
```python
def fact(num):
    if num <= 0:
        return 1
    return num * fact(num - 1)

a = int(input())
b = int(input())
print(fact(a) - fact(b))
```
### Output:
![image](https://github.com/user-attachments/assets/0451e10e-1a26-4c9f-992b-07faf897a2d4)
### Result:
Thus the given program was executed Successfully.



 

