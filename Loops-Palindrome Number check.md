Loops in Python: Palindrome Number Checker
🎯 Aim
To write a Python program that checks whether a given number is a palindrome using loops.

🧠 Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
🧾 Program
Add code Here

num = int(input("Enter a number: "))
temp = num
rev = 0

while temp > 0:
    rev = (rev * 10) + (temp % 10)
    temp = temp // 10

if num == rev:
    print(num, "is a palindrome number.")
else:
    print(num, "is not a palindrome number.")
Output
Screenshot 2025-10-20 132708
Result
The program successfully checks whether a given number is a palindrome using loops.
