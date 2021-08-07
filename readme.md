Pretest – John (Yohannes)
Deadline: 1 August 2021
Turn your answer as .py file(john-doe.py) to Asabeneh privately on Telegram
1. What is programming (5 points)
•	List down some of the importance of Python programming language
•	Answer: - compatible for all platforms, most used in data manipulating, versatile….
•	What version of Python that you are currently using?
•	3.9.1
•	What code editor are you using?
•	Atom, Pycharm, visualCode, Spider
•	What is the Python interactive shell?
•	Python IDE
•	How do you open the Python interactive shell and how do you close it?
•	cmd>python
•	What is the extension of the Python script file?
•	.py
2. Comments (2 points)
•	What is the use of a comment in programming?
Describing and sharing code explanation 
•	Write an example of a single line Python comment
# Setting timer to sleep for few minutes
#print(‘You cake is ready, please turn the oven off and enjoy’) 
•	Write an example of multiline Python comment
‘’’ you can have multiple line 
of comments by using 
the three single quote ‘’’ or 
“”” you can have multiple line 
of comments by using 
the three double quote “””
3. Data types (5point)
•	List all the data types you know and give one example for each data types
1.	Text type: str
2.	Numeric types: int, float, complex
3.	Sequence types: - list, tuple, range 
4.	Mapping: - dict
5.	Set types: - set, frozenset
6.	Boolean type: bool
7.	Binary type: bytes, bytearray, memoryview
How do you check Python data types?
•	Print(type())
4. Variables (4 points)
•	Declare a variable of all data types
first_name = input(‘write your first name here:   ‘)
age = 25
height = 5.75
•	Check the data types of your variables
Print(type(first_name))
Print(type(age))
Print(type(height))
5. Operations (5 points)
You have 4 and 3 as operands. Do the following operations(addition, subtraction, multiplication, division, modulus, floor division, exponentiation)
Print (4 + 3)
Print(4 - 3)
Print (4 * 3)
Print(4/3)
Print( 4 % 3)
Print (4 // 3)
Print(4**3)
6. Getting user input (5 points)
Write a small script that can calculate the age of a person. The program asks the user to enter birth year and the current year.
Enter your birth year: 1950
Enter the current year: 2020
You are 70 years old.
Answer: -
#import datetime
birth_year = int(input("Enter your birth year: "))
current_year = int(input("Enter the current year:  "))
#current_year = datetime.date.today().year
age_year = current_year - birth_year
print("Your are: ", age_year, "Years old")
Write a small script that can calculate the weight of an object on Earth. The program asks user to enter mass and calculate the weight.
Enter your weight: 100
Your weight is 98.1 N.

weight = int(input("Enter your weight:  "))
mass = float(9.81)
body_weight = weight * mass
print("Your weight is:    " + str(body_weight)+ " "+ "N" )
7. Strings (10 Points)
•	Concatenate the string 'Coding', 'For', 'All' to a single string, 'Coding For All'
a = 'Coding'
b = 'For'
c = 'All'
print(a + " " + b + " "+ c)
•	Declare a variable name company and assign it to an initial value "Coding For All".
company = “Coding For All”
•	Print the length of the company string using len() method
len(company)
•	Change all the string to uppercase letters using upper() method
Company.upper()
   'CODING FOR ALL'
•	Change all the string to lowercase letters using lower() method
company.lower()
'CODING FOR ALL'

company.swapcase()

   'cODING fOR aLL'

•	Use capitalize(), title(), swapcase() methods to format the value stored in the variable name company
company.capitalize()
'Coding for all'
company.title()
'Coding For All'
•	Slice out the first word of the company string
Company[0:6]
'Coding'

•	Replace the word coding in the string 'Coding For All' to Python using replace or other methods.
company.replace("Coding", "Python")
'Python For All'

•	Change Python for All to Python for Everyone using the replace method or other methods
X = company.replace("Coding", "Python")
x.replace(“All”, “Everyone”)
   'Python For Everyone’
•	Split the string 'Coding For All' at the space using split() method
company.split(" ")
   ['Coding', 'For', 'All']
•	"Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon" split the string at the comma
x = "Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon"
x.split(", ")
['Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon']
•	What is character at index 10 in "Coding For All"
Company [10]
      ' '
8.Conditionals (10 points)
•	Get user input using input(“Enter your age:”). If the user is 18 or older, give feedback: You are old enough to drive but if not 18 give feedback to wait for the years he supposed to wait for.
    Enter your age: 30
    You are old enough to drive.
    Enter your age:15
    You are left with 3 years to drive.
1/
age = int(input("Enter your age:  "))
if age >= 18:
    print("You are old enough to drive")
else:
    print("You are left with 3 years to drive ") 

•	Check if the season is Autumn, Winter, Spring, or Summer. If the user input is:
September, October or November, the season is Autumn. December, January or February, the season is Winter. March, April or May, the season is Spring June, July or August, the season is Summer


month = input("Input the month: ")
if month in ('January', 'February', 'March'):
    season = 'winter'
elif month in ('April', 'May', 'June'):
    season = 'spring'
elif month in ('July', 'August', 'September'):
    season = 'summer'
else:
    season = 'autumn'
print("Season is",season)
9. Loops (10 points)
1.	Iterate 0 to 10 using for loop, do the same using while and do while loop. 
2.	Iterate 10 to 0 using for loop, do the same using while and do while loop. 
3.	Write a loop that makes seven calls to print () to output the following triangle:
    #
    ##
    ###
    ####
    #####
    ######
    #######
n = int(input('Enter number of rows : '))
 
i = 1
while i <= 7 :
    j = 1
    while j <= i:
        print("#", end = " ")
        j += 1
    print()
    i += 1
•	Use nested loops to create the following:
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
    # # # # # # # #
num_rows = 8
num_cols = 7

for i in range(num_rows):
    print('#', end=' ')
    for j in range(num_cols-1):
        i*=j
        print('*', end=' ')
    print('')
•	Iterate the list, ['Python', 'NumPy','Pandas','Data Science', AI','ML'] using a for loop and print out the items.
•	Use for loop to iterate from 0 to 100 and print only even numbers
for i in range(0,100): 
    if i%2==0: 
       print(i)
•	Use for loop to iterate from 0 to 100 and print only odd numbers
for i in range(0,100): 
if i%2!=0: 
   print(i)
•	Use for loop to iterate from 0 to 100 and print and print the sum of all numbers. The sum of all numbers is 5050.
n = int(input("Enter Number to calculate sum:   "))
sum = 0
for num in range(n+1):
    sum = sum+num
print("SUM of first ", n, "numbers is:     ", sum )

Enter Number to calculate sum:   100
SUM of first  100 numbers is:      5050
 
•	Use for loop to iterate from 0 to 100 and print the sum of all evens and the sum of all odds. The sum of all evens is 2550. And the sum of all odds is 2500.
Sum of all odds
n = int(input("Enter number to calculate sum:   "))
sum = 0
for num in range(n+1):
    if num%2!=0: 
        sum = sum+num
print("SUM of first ", n, "numbers is:     ", sum )

Enter Number to calculate sum:   100
SUM of first  100 numbers is:      2500

Sum of all evens
n = int(input("Enter number to calculate sum:   "))
sum = 0
for num in range(n+1):
    if num%2==0: 
        sum = sum+num
print("SUM of first ", n, "numbers is:     ", sum )
Enter Number to calculate sum:   100
SUM of first  100 numbers is:      2550
10. Lists (10 points)
•	Declare a list called mixed_data_types,put different data types and in your array and the array size should be greater than 5
mixed_data_types = [15, 9.18, “abcd”, “ab12d”, {apple}]
•	Declare a list variable name it companies and assign initial values Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon.
companies = ["Facebook", "Google", "Microsoft", "Apple", "IBM", "Oracle", "Amazon"]
•	Print the number of companies in the list
companies = ["Facebook", "Google", "Microsoft", "Apple", "IBM", "Oracle", "Amazon"]
number_of_companies = len(companies)
print(number_of_companies)

•	Print the first, middle and last company in the list
companies[0]
companies[3]
companies[7]
•	Print out each company
print(*companies, sep = "\n")
Facebook
Google
Microsoft
Apple
IBM
Oracle
Amazon

•	Change companies to uppercase and print them out
•	Print the list like a sentence: Facebook, Google, Microsoft, Apple, IBM, Oracle and Amazon are big IT companies.
•	Check if a certain company exists in the it_companies list. If it exist return the company else return a company is _not found.
•	Filter out companies which have more than one 'o' without the filter method
•	Sort the array using sort() method
•	Reverse the array without method
•	Reverse the array using method
11. Functions (10 Points )
•	Declare a function full_name and now it takes firstName, lastName as a parameter and it returns your full name.
def full_name(firstName, lastName):
       print(firstName + " " + lastName)
•	Declare a function add_two_numbers and it takes two parameters and it returns the sum.
def add_two_numbers(x, y):
    print(x + y)
•	Temperature in oC can be converted to oF using this formula: oF = (oC x 9/5) + 32. Write a function which converts oC to oF convert_celcius_to_fahrenheit.
oC = float(input("Enter temperature in celsius: "))
oF = (oC * 9/5) + 32
print('%.2f oC is: %.2f oF' %(oC, oF))
•	Body mass index(BMI) is calculated as follows: bmi = weight in Kg / (height x height) in m2. Write a function that calculates bmi. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is underweight, normal, overweight or obese based the information given below.
The same groups apply to both men and women. Underweight: BMI is less than 18.5 Normal weight: BMI is 18.5 to 24.9 Overweight: BMI is 25 to 29.9 Obese: BMI is 30 or more
•	Quadratic equation is written as follows: ax2 + bx + c = 0. Write a function that calculates value or values of a quadratic equation solutions, solve_quadratic_equation.
•	Declare a function name _print_list. It takes list as a parameter and it prints out each element of the list.
•	Declare a function name swap_values. This function swaps the value of x to y.
    swap_values(3, 4) # x => 4, y=>3
    swap_values(4, 5) # x = 5, y = 4
•	Declare a function name reverse_list. It takes a list as a parameter and it returns the reverse of the array (don't’ use method).
    pirnt(reverseArray([1, 2, 3, 4, 5]))
    [5, 4, 3, 2, 1]
    print(reverseArray(["A", "B", "C"]))
    ["C", "B", "A"]
•	Declare a function name sum_of_numbers. It takes a number parameter and it adds all the numbers in that range.
•	Declare a function name sum_of_evens. It takes a number parameter and it adds all the even numbers in that - range.
    print(evens_and_odds(100))
    The number of odds are 50.
    he number of evens are 51.
•	Write a function which takes any number of arguments and return the sum of the arguments
sum_all_numbers(1, 2, 3) // -> 6
sum_all_numbers(1, 2, 3, 4) // -> 10

1/def add(*args):
    print(sum(args))


