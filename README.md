# Python-If-Else

# Challenge:
- Given an integer, n, perform the following conditional actions:
  - If  is odd, print Weird
  - If  is even and in the inclusive range of  to, print Not Weird
  - If  is even and in the inclusive range of  to, print Weird
  - If  is even and greater than, print Not Weird

- A single line containing a positive integer, n. 

- Constraint is the following: 1 <= n <= 100

- Print Weird if the number is weird. Otherwise, print Not Weird.

# Solution:
- if n%2 != 0:
-       print("Weird")
-   else:
-       if n>=2 and n<=5:
-           print("Not Weird")
-       elif n>=6 and n<=20:
-           print("Weird")
-       else:
-           print("Not Weird")

- Explanation on if n%2 ! - 0
- n is the variable representing the number to be checked.
- % is the modulo operator, which calculates the remainder when n is divided by 2.
- != is the not equal to operator, which checks if the result of the modulo operation is not equal to 0.
- if n % 2 != 0: checks if the remainder of n divided by 2 is not equal to 0, indicating that n is an odd number.
