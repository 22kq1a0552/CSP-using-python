1. Check if a number is Positive, Negative, or Zero
   nums=map(float,input("enter a numbers :").split(" "))
for num in nums:
    if num>0:
        print(f"{num} is positive number")
    elif num<0:
        print(f"{num} is negative number")
    else:
        print(f"{num} is a zero")
        
<img width="1265" height="340" alt="image" src="https://github.com/user-attachments/assets/9ae62192-c3cc-4e11-a6bd-cf7b05ed75d0" />

2.Write a Python program that takes a positive integer as input and calculates its factorial using a for loop. Display the factorial as the output. 
n=int(input("enter a number:"))
fact=1
for i in range(1,n+1):
    fact=fact*i
print(fact)
<img width="1115" height="220" alt="image" src="https://github.com/user-attachments/assets/98ffbb25-1b30-47c6-8e4f-f1962355cf20" />

3. Write a Python program that takes two numbers (which may be integers or decimals) as input from the user and calculates their sum. Display the result.
   num1=float(input("enter num1:"))
num2=float(input("enter num2:"))
total= num1+num2
print(total)
<img width="1157" height="221" alt="image" src="https://github.com/user-attachments/assets/7532a116-6e77-491d-a007-39a26c23eaf8" />


4.Write a Python program that asks the user to enter a word or number and checks whether it is a palindrome.
user_input=map(input("Enter a word:").split(" "))
for input in user_input:
    if user_input==user_input[::-1]:
        print("plaindrome")
    else:
        print("nota plaindrome")
<img width="1274" height="216" alt="image" src="https://github.com/user-attachments/assets/a97e3aa8-021d-47b8-8813-4a56f4443d4a" />

5.  Check if a given year is a leap year.
   years=map(int,input("Enter a year:").split())
for year in years:
    if (year % 4 ==0 and year % 100!=0) or (year % 400==0):
        print(f"{year} is a leap year")
    else:
        print(f"{year} is not a leap year")

<img width="1183" height="184" alt="image" src="https://github.com/user-attachments/assets/8d591d83-b282-47f0-bd53-c8d9070c3f93" />
