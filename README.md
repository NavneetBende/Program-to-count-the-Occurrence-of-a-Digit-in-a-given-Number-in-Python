# Program-to-count-the-Occurrence-of-a-Digit-in-a-given-Number-in-Python

Occurrence of a Digit in a given Number in Python
 
 
Here, in this page we will discuss the program to find the Occurrence of a Digit in a given Number in Python programming language. We will discuss different methods to solve this problem.
number of times x digit occurs in python
Example :
Input : Enter a number : 897982
             Enter the digit : 9
Output :  2
Explanation : The digit 9 occurs twice
Method Discussed :
Method 1 : Using loops
Method 2 : Using String
 
Method 1 :
Declare variable count that will count the required number of occurrences
Take a while loop. 
Check if(n%10 ==d)
If yes, then increment the value of count by 1.
Set, n=n//10
Print the value of count.
Method 1 : Code in Python
Run
#Write a program to print the Occurrence of a Digit in a given Number in Python
def countOccurrances(n, d):
    count = 0
 
    # Loop to find the digits of N
    while (n > 0):
 
        # check if the digit is D
        if(n % 10 == d):
            count = count + 1
  
        n = n // 10
 
    return count
 
# Driver code
d = 2
n = 828282
print(countOccurrances(n, d))
Output:
3
Related Pages
Convert digit/number to words

Counting number of days in a given month of a year
 
Finding number of integers which has exactly x divisors

Finding Roots of a quadratic equation

Power of a Number 

Method 2 :
In this method we will convert the number and digit into string, and then count them.

Method 2 : Code in Python
Run
#Write a program to print the Occurrence of a Digit in a given Number in Python
#Write a program to print the Occurrence of a Digit in a given Number in Python

Number = 828282
Digit = 2

#initialize Strings
String1 = str()
String2 = str()

#typecast int to str
String1 = str(Number)
String2 = str(Digit)

#count and print the occurrence
#Count function will return int value 
#so change it's type to string and concatenate it
print(String1.count(String2))

Output:
3
