# Exam subject: python
### topic: python List
#### Question 1: Turn every item of a list into its square
Given a list of numbers. write a program to turn every item of a list into its square.

Given:
```
numbers = [1, 2, 3, 4, 5, 6, 7]
```

Expected output:
```
[1, 4, 9, 16, 25, 36, 49]
```
Hint:
Iterate numbers from a list one by one using a for loop and calculate the square of the current number


#### Question 2: Reverse a list in Python

Given:
```
list1 = [100, 200, 300, 400, 500]
```

Expected output:
```
[500, 400, 300, 200, 100]
```
Hint:
Use the list function reverse()


### topic: python loop

#### Question 3: Print first 10 natural numbers using for loop


Expected output:
```
1
2
3
4
5
6
7
8
9
10
```


#### Question 4:  Print the following pattern
Write a Python code to print the following number pattern using a loop.

Expected output:
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
Hint:
Decide the row count, i.e., 5, because the pattern contains five rows
Run the outer loop 5 times using for loop and range() function
Run inner loop i+1 times using for loop and range() function
In the first iteration of the outer loop, the inner loop will execute one time
In the second iteration of the outer loop, the inner loop will execute 2 time
In the third iteration of the outer loop, the inner loop will execute 3 times, and so on, till row 5
print the value of j in each iteration of the inner loop (j is the inner loop iterator variable)
Display an empty line at the end of each iteration of the outer loop (empty line after each row)

#### Question 5:  Print the following pattern
Write a Python program to accept a number from a user and calculate the sum of all numbers from 1 to a given number

For example, if the user entered 10, the output should be 55 (1+2+3+4+5+6+7+8+9+10)

Expected output:
```
Enter number 10
Sum is:  55
```

Hint:
Approach 1: Use for loop and range() function

Create variable s = 0 to store the sum of all numbers
Use Python 3’s built-in function input() to take input from a user
Convert user input to the integer type using the int() constructor and save it to a variable n
Run loop n times using for loop and range() function
In each iteration of a loop, add a current number (i) to variable s
Use the print() function to display the variable s on screen
Approach 2: Use the built-in function sum(). The sum() function calculates the addition of all numbers from 1 to a given number.
