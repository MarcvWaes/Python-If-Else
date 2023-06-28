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

