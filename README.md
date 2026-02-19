Experiment 8: Study of For Loop, Nested Loop and Patterns in Python

Aim:
To study and implement for loops, nested loops, matrix operations, prime number generation, and pattern printing in Python.

Theory
1. Looping in Python
A loop is a control structure that allows repeated execution of a block of code as long as a condition is satisfied or for a fixed number of iterations. Loops reduce redundancy and improve efficiency.
Python provides two types of loops:
for loop
while loop
This experiment mainly focuses on the for loop.
2. For Loop
The for loop is used when the number of iterations is known beforehand. It is commonly used with the range() function.
3. Nested Loops
A loop inside another loop is called a nested loop.
Nested loops are commonly used for:
Matrix operations
Pattern printing
Table generation
In matrix operations:
Outer loop → Controls rows
Inner loop → Controls columns
4. Matrix in Python
A matrix in Python is represented using a list of lists.

Programs and Algorithms

Program : Print Numbers from 1 to 5

Algorithm:
Step 1: Start.
Step 2: Initialize loop variable i using range from 1 to 5.
Step 3: Print value of i.
Step 4: Repeat Steps 2 and 3 until range ends.
Step 5: Stop.
Program 3: Print Only Odd Numbers from 1 to 10

Algorithm:
Step 1: Start.
Step 2: Initialize loop variable i using range from 1 to 10 with step size 2.
Step 3: Print value of i.
Step 4: Repeat Steps 2 and 3 until range ends.
Step 5: Stop.
Program 4: Sum of First N Natural Numbers

Algorithm:
Step 1: Start.
Step 2: Accept integer n.
Step 3: Initialize variable total = 0.
Step 4: Initialize loop variable i from 1 to n.
Step 5: Add i to total.
Step 6: Repeat Steps 4 and 5 until loop ends.
Step 7: Display total.
Step 8: Stop.
Program 5: Display a 3×3 Matrix Using Nested Loops

Algorithm:
Step 1: Start.
Step 2: Define matrix A as a 3×3 list.
Step 3: Initialize outer loop i from 0 to 2.
Step 4: Initialize inner loop j from 0 to 2.
Step 5: Print element A[i][j].
Step 6: After inner loop ends, print newline.
Step 7: Repeat Steps 3 to 6 until outer loop ends.
Step 8: Stop.
Program 6: Multiplication of Two 3×3 Matrices

Algorithm:
Step 1: Start.
Step 2: Define matrix A of size 3×3.
Step 3: Define matrix B of size 3×3.
Step 4: Initialize result matrix Result with all elements as 0.
Step 5: Initialize outer loop i from 0 to 2.
Step 6: Initialize second loop j from 0 to 2.
Step 7: Initialize third loop k from 0 to 2.
Step 8: Compute Result[i][j] = Result[i][j] + A[i][k] × B[k][j].
Step 9: Repeat Step 7 and 8 until k loop ends.
Step 10: Repeat Steps 6 to 9 until j loop ends.
Step 11: Repeat Steps 5 to 10 until i loop ends.
Step 12: Display result matrix.
Step 13: Stop.
Program 7: Display 3×3 Matrix Using List Traversal

Algorithm:
Step 1: Start.
Step 2: Define matrix A as a 3×3 list.
Step 3: Traverse each row r in matrix A.
Step 4: Print row r.
Step 5: Repeat Steps 3 and 4 until all rows are printed.
Step 6: Stop.
Program 8: Print Prime Numbers Between 2 and 49

Algorithm:
Step 1: Start.
Step 2: Initialize loop variable num from 2 to 49.
Step 3: For each num, initialize inner loop variable i from 2 to num - 1.
Step 4: If num % i == 0, terminate inner loop using break.
Step 5: If inner loop completes without break, print num.
Step 6: Repeat Steps 3 to 5 until outer loop ends.
Step 7: Stop.
Program 9: Print Inverted Right Triangle Pattern

Algorithm:
Step 1: Start.
Step 2: Initialize loop variable i from 10 down to 1.
Step 3: Print i number of asterisks.
Step 4: Repeat Steps 2 and 3 until loop ends.
Step 5: Stop.
Program 10: Print Pyramid Pattern

Algorithm:
Step 1: Start.
Step 2: Assign rows = 5.
Step 3: Initialize loop variable i from 1 to rows.
Step 4: Print spaces equal to (rows - i).
Step 5: Print "*" repeated i times.
Step 6: Repeat Steps 3 to 5 until loop ends.
Step 7: Stop.
Program 11: Print Inverted Pyramid Pattern

Algorithm:
Step 1: Start.
Step 2: Assign n = 5.
Step 3: Initialize loop variable i from 0 to n - 1.
Step 4: Print spaces equal to i.
Step 5: Print "*" repeated (n - i) times.
Step 6: Repeat Steps 3 to 5 until loop ends.
Step 7: Stop.

Result
All programs related to for loops, nested loops, matrix operations, prime number generation, and pattern printing were successfully implemented and executed.
