 
# Introduction-to-python

Introduction to Python 

# Week 1   

 ## Day 1  

 

What is Python  

It’s a popular programing language. It was created by Guido van Rossum and released in 1991. 

It is used for web development (server-side). 

 

What can python do. 

Python can be used on a server to create web applications. 

Python can be used alongside software to create workflows. 

Python can connect to database systems. It can also read and modify files. 

Python can be used to handle big data and perform complex mathematics. 

Python can be used for rapid prototyping, or for production-ready software development. 

 

Python in the job Market. 

Python was in high demand in the job market and was widely used in various industries.  

 

Python 

Versatility: Python's versatility made it a popular language in various fields, including web development, data science, machine learning, automation, and more. 

Data Science and Machine Learning: Python was the go-to language for data scientists and machine learning engineers, with libraries like NumPy, Pandas, and scikit-learn facilitating data analysis and modeling. 

Web Development: Python's frameworks, like Django and Flask, were used to develop web applications. Its simplicity and readability made it a top choice for both beginners and experienced developers. 

Automation and Scripting: Python was widely used for automating repetitive tasks, making it valuable in system administration, DevOps, and other areas. 

Job Opportunities: The demand for Python developers, data analysts, and data scientists remained high, with many job openings and competitive salaries. 

Remote Work: Python's popularity contributed to the growth of remote work opportunities, as many Python-related tasks could be performed remotely. 

Future Outlook: Python's continued growth in popularity and its ecosystem, especially in data science and machine learning, suggested that it would remain a valuable skill in the job market. 

 

The history of Python 

 

Conception and Development (Late 1980s): Python was created by Guido van Rossum, a Dutch programmer. He started working on Python in the late 1980s and released the first version, Python 0.9.0, in February 1991. 

 Python's design philosophy emphasized code readability and ease of use. 

Python 2 and 3 Split (2008): In 2008, Python went through a significant change with the release of Python 3. 

This version introduced several backward-incompatible changes, aiming to enhance the language's consistency and remove redundancy. However, it also led to a division in the Python community, as Python 2 code was not compatible with Python 3. 

Growth in Popularity (2000s): Throughout the 2000s, Python saw a steady increase in popularity. Its clean and readable syntax, along with an extensive standard library, attracted developers in various domains. 

 

Python in Web Development (2000s-2010s): Frameworks like Django and Flask emerged, making Python a popular choice for web development. These frameworks simplified the creation of web applications. 

Data Science and Machine Learning (2010s): Python gained prominence in data science and machine learning with the development of libraries like NumPy, Pandas, and scikit-learn. Python became the de facto language for data analysis and machine learning projects. 

Community and Open Source (Ongoing): Python's success is closely tied to its active and passionate community. The language is open source, and many developers contribute to its growth through the Python Software Foundation. 

Python 3 Adoption (Ongoing): Despite the initial controversy, Python 3 gradually gained widespread adoption, and the community transitioned from Python 2. Python 2 reached its end of life in January 2020, and Python 3 is now the primary version. 

Continued Evolution (Ongoing): Python continues to evolve with regular releases, introducing new features, optimizations, and improvements to maintain its relevance in a rapidly changing technology landscape. 

Today, Python is one of the most popular and versatile programming languages, used in web development, data science, machine learning, scientific computing, and more.Its community and ecosystem continue to thrive, making it a vital part of the software development world. 

 

Comments in Python  

 

Comments can be used to explain Python code. 

Comments starts with a # and python will ignore them. 

 

Example  

# this is a comment 

 

A comment doesn’t have to be a text to explain the code, it can be used to prevent Python from executing code. 

Python will ignore string literals that are assigned to a variable, you can add a multi string (tripe quote) in your code, and place your comment inside. 

         Example 

       “ ‘’ ‘’ 

        This is a comment written in more than just one line 

        ‘’ ‘’ ‘’ 

If the string is not assigned to a variable, python will read the code, but ignore it. And you have made a multiline comment. 

 

 

Creating Applications using Python 

 

I have learned how print Strings 

 

Example  

 

Print (‘Hello world’) 

 

Learned how to use excape characters  

 

Example  

 

Print ( ‘Hello \nWorld’ ) 

 

 

 

 

 

 

 

 

 

 

 

Introduction to Variables 

 

 

Day 2 

 

Variables are containers for storing data value. 

Python has no command for declaring a variable. 

A variable is created the moment you first assign a value to it. 

 

Example  

X = 5 

Y = ‘’ John “ 

Print (x) 

Print (y) 

 

 

Variables do not need to be declared with any type and can even change type after they have been set. 

 

 Example 

 

X = 4   ( x is of type int) 

X = ‘’ Sally “  ( x is now of type str) 

Print (x) 

 

 

String variable can be declared either by using single or double qoutes 

 

Example 

 

X = “John” 

 

# is the same as  

 

X = ‘John’ 

 

Variable names are case-sensitive. 

 

Example 

 

  a = 4 

A= “Sally” 

# A will not overwrite a 

 

 

 

Variables are a temporary storage space in a computer’s memory. 

 When a variable’s value changes the program’s current state also changes.  

A variable acts as a container to hold a different number of data items or values.  

All programming languages use variables, as they are among the most important elements in programming, and that is why a good understanding of variables will only make your job easier when writing programs.  

Variables are also used to move data between functions; this will be discussed later. 

Every variable is created with an initial value. 

  

 

 

 

A variable can be in three states: 

 

         Variable creation (Declaration) 

          Variable assignment (Initialization) 

          Variable changed (Execution) 

 

Once the code which created the variable has finished executing, the variable is destroyed. 

In Python, variables are defined in a standard way, by using the assignment character (=).  

This changes the value of the variable. Naming conventions specify the way in which variables should be named.  

This standard is used to make code more readable, and thus easier to understand. 

The rules include the start and continuation characters.  

Variable names may contain any upper or lower case letter (A–Z, a–z), a number, or the underscore character.  

They may not begin with a number or contain spaces.  

Continuation characters are any characters except whitespace characters like tab and space. 

 

Here are a few examples of valid variable names: 

c 

ref_number 

admin 

aVeryLongName 

 

Here are a few examples of invalid variable names: 

True 

$name 

12Graph 

 

In Python identifiers are case sensitive, so for example, firstName, FirstName, FIRSTNAME, and firstname are four different identifiers.  

A second rule is that variables cannot have the same name as Python’s keywords.  

We can find out what keywords are in Python, by using the function called dir().  

If this function is called with the __builtins__ attribute, it returns a list of Python’s built-in attributes. 

The __builtins__ module contains all Python’s built-in attributes, which can be used with the dir()function.  

 

The ones that are returned are identified with the following characteristics: 

Python’s built-in exceptions start with a capital letter. 

The rest are either functions or data type names. 

Identifiers that start and end with one or two underscores are special methods. 

  

 

 

 

Using Variables 

 

All variables must be assigned to a data type like a string (a series of characters) or an integer (positive or negative whole numbers) 

Using a variable in Python involves declaring a name to represent a value, which can be of various data types, such as numbers, strings, or other objects.  

 

Key points about using a variable in Python include: 

  

1. **Declaration**: Variables in Python are created by assigning a name to a value.  

 

For example,  

`x = 5` assigns the value 5 to the variable `x`. 

 

2. **Dynamic Typing**: Python is dynamically typed, meaning you don't need to specify the data type explicitly.  

Python infers the data type based on the assigned value. 

  

3. **Naming Rules**: Variable names should start with a letter or underscore, followed by letters, digits, or underscores. They are case-sensitive. 

  

4. **Data Storage**: Variables store and manage data, allowing you to access and modify values throughout your code. 

  

5. **No Declaration**: Unlike some other programming languages, you don't need to declare the type of variable explicitly. Python handles this behind the scenes. 

  

6. **Reassignment**: You can change the value of a variable after it's declared. For example, `x = 5` can later be changed to `x = 10`. 

  

7. **Scoping**: Variables can have local or global scope. Local variables are limited to a specific block or function, while global variables can be accessed throughout the program. 

  

8. **Data Manipulation**: Variables enable you to perform various operations, such as mathematical calculations or string concatenation. 

  

9. **Dynamic Values**: Variables can hold dynamic values that can change during the program's execution, making Python suitable for tasks that require adaptability. 

  

In summary, Python variables are essential for data storage and manipulation. They are easy to work with, dynamic, and versatile, contributing to the readability and flexibility of Python code. 

 

 

 

 

 

 

Casting  

 

Casting can be done in two ways  

 

Implicitly 

The compiler automatically casts a value from one data type to another when assured that there will be no data lost. 

         

       For example  

 

          Casting from an integer variable to a floating-pointer variable or casting from                 an integer variable or casting from an integer variable to another integer variable. 

 

Explicitly: A value cannot be automatically cast from one data type to another if it will result in data loss. Extra code must be written to ensure that the value stays the same and only the data type changes. 

         

For example,  

casting from a floating-point value to an integer value 

 
Notice that no errors occur when converting from an integer to a float. This will always be the case because an integer can be cast to a float data type implicitly because there will be no data loss. However the reverse is not true; a floating-point number cannot be implicitly cast into an integer as this will result in data loss (all data after the precision (.) will be lost), because the floating-point value does not get rounded off to the nearest whole number when implicitly converting to an integer (as seen in the above example). 

The third printed line casts a string to a float successfully, because s_number is in the correct format. The rules to convert a string to a float are: 

The string should only contain numbers. 

Other than numbers the following are allowed: 

Only one dot (.) character. Indicates the decimal starts after the dot (.) character. 

A ‘+’ or ‘−‘ character at the beginning of the string. This indicates that the number is either positive or negative. 

 
 

Day2  

 

integer 

 

In Python, integers are a data type used to represent whole numbers, both positive and negative, without any decimal or fractional parts. They are integral to mathematical operations and are widely used in programming. Python's support for arbitrarily large integers makes it a versatile choice for numerical calculations. 

  

**Examples:** 

  

1. **Positive Integers:** 

   ```python 

   x = 5 

   y = 100 

   ``` 

  

2. **Negative Integers:** 

   ```python 

   temperature = -10 

   debt = -5000 

   ``` 

  

3. **Mathematical Operations:** 

   ```python 

   a = 10 

   b = 3 

  

   # Addition 

   sum_result = a + b  # sum_result is 13 

  

   # Subtraction 

   diff_result = a - b  # diff_result is 7 

  

   # Multiplication 

   product_result = a * b  # product_result is 30 

  

   # Division 

   division_result = a / b  # division_result is 3.3333333333333335 

   ``` 

  

4. **Large Integers:** 

   Python supports large integers without an upper limit, which is useful for calculations that involve very large or precise numbers. 

   ```python 

   large_number = 1234567890123456789012345678901234567890 

   ``` 

  

5. **Converting Other Types to Integers:** 

   You can convert other types, like strings or floats, to integers using functions like `int()`: 

   ```python 

   age_str = "30" 

   age = int(age_str)  # Converts the string to an integer 

   ``` 

  

Integers are fundamental for numerical processing, counting, indexing, and various mathematical operations in Python. 

 

 

 

 

Booleans   

In Python, Booleans are a data type that represents two truth values: `True` and `False`. Booleans are often used in conditional statements, loops, and logical operations to control the flow of a program. They help make decisions based on the truth or falsity of expressions. Booleans are fundamental for building logical and decision-making functionality in Python. 

  

**Examples:** 

  

1. **True and False Values:** 

   ```python 

   is_python_fun = True 

   is_learning = False 

   ``` 

  

2. **Comparison Operators:** 

   Booleans are commonly used with comparison operators to evaluate conditions: 

   ```python 

   x = 5 

   y = 10 

  

   is_greater = x > y  # False 

   is_equal = x == y   # False 

   ``` 

  

3. **Logical Operators:** 

   Logical operators such as `and`, `or`, and `not` work with Booleans to create complex conditions: 

   ```python 

   sunny = True 

   warm = False 

  

   is_good_day = sunny and not warm  # True 

   ``` 

  

4. **Conditional Statements:** 

   Booleans are used in `if`, `elif`, and `else` statements to control program flow: 

   ```python 

   age = 25 

  

   if age >= 18: 

       can_vote = True 

   else: 

       can_vote = False 

   ``` 

  

5. **Loop Control:** 

   Booleans determine when loops continue or terminate: 

   ```python 

   while True: 

       # This loop runs indefinitely until a break condition is met. 

       user_input = input("Enter 'quit' to exit: ") 

       if user_input == 'quit': 

           break 

   ``` 

  

6. **Function Returns:** 

   Functions can return Booleans to indicate success or failure: 

   ```python 

   def is_even(number): 

       return number % 2 == 0 

  

   result = is_even(6)  # True 

   ``` 

Booleans are essential for decision-making and control structures in Python. They enable you to write code that responds to different conditions and make your programs dynamic and adaptable. 

 

Floating point numbers 

  

Floating-point numbers in Python are a data type used to represent real numbers, including numbers with decimal fractions. They are suitable for a wide range of mathematical and scientific calculations. Python uses the IEEE 754 standard to store and perform operations on floating-point numbers. However, due to the nature of floating-point representation, there can be issues with precision and rounding in certain calculations. 

  

**Examples:** 

  

1. **Basic Floating-Point Numbers:** 

   ```python 

   pi = 3.14159265359 

   gravity = 9.81 

   ``` 

  

2. **Mathematical Operations:** 

   Floating-point numbers are used in various mathematical operations. 

   ```python 

   a = 5.2 

   b = 2.0 

  

   # Addition 

   sum_result = a + b  # sum_result is 7.2 

  

   # Subtraction 

   diff_result = a - b  # diff_result is 3.2 

  

   # Multiplication 

   product_result = a * b  # product_result is 10.4 

  

   # Division 

   division_result = a / b  # division_result is 2.6 

   ``` 

  

3. **Precision and Rounding:** 

   Due to binary representation, some numbers can't be precisely represented. 

   ```python 

   a = 1.1 

   b = 2.2 

  

   sum_result = a + b  # sum_result is not exactly 3.3 due to precision limitations 

   ``` 

  

4. **Scientific Notation:** 

   You can represent very large or very small numbers using scientific notation. 

   ```python 

   speed_of_light = 2.998e8  # 299,800,000 m/s 

   plank_constant = 6.626e-34  # 0.0000000000000000000000000000006626 J·s 

   ``` 

  

5. **Type Conversion:** 

   You can convert other types to floating-point numbers using `float()`: 

   ```python 

   number_str = "3.14" 

   converted_number = float(number_str)  # Converts the string to a float 

   ``` 

  

Floating-point numbers are versatile for scientific and mathematical calculations but require an understanding of their limitations regarding precision. Developers should be cautious when comparing floating-point numbers for equality due to potential rounding errors. 

 

 

 

 

 

 

 

Lambda expressions 

  

in Python are a way to create small, anonymous, and inline functions. They are also known as lambda functions or anonymous functions. Lambda expressions are typically used for short, simple operations where defining a full function using `def` is unnecessary. They are often employed with higher-order functions like `map`, `filter`, and `reduce`, as well as in situations where a function is used temporarily and does not need a formal name. 

  

**Examples:** 

  

1. **Basic Lambda Expression:** 

   ```python 

   add = lambda x, y: x + y 

   result = add(5, 3)  # result is 8 

   ``` 

  

2. **Lambda with `map`:** 

   Using a lambda function to apply an operation to each element of a list. 

   ```python 

   numbers = [1, 2, 3, 4, 5] 

   squared = list(map(lambda x: x**2, numbers)) 

   # squared is [1, 4, 9, 16, 25] 

   ``` 

  

3. **Lambda with `filter`:** 

   Using a lambda function to filter elements in a list based on a condition. 

   ```python 

   numbers = [1, 2, 3, 4, 5] 

   even_numbers = list(filter(lambda x: x % 2 == 0, numbers)) 

   # even_numbers is [2, 4] 

   ``` 

  

4. **Sorting with Lambda:** 

   Using a lambda function as a key for sorting a list of tuples. 

   ```python 

   people = [("Alice", 25), ("Bob", 32), ("Charlie", 18)] 

   people.sort(key=lambda person: person[1])  # Sort by age 

   # Result: [("Charlie", 18), ("Alice", 25), ("Bob", 32)] 

   ``` 

  

5. **Lambda in Higher-Order Function:** 

   Using lambda with `sorted` to sort a list of strings by their length. 

   ```python 

   words = ["apple", "banana", "cherry", "date"] 

   words.sort(key=lambda word: len(word)) 

   # Result: ["date", "apple", "cherry", "banana"] 

   ``` 

  

Lambda expressions are concise and convenient for simple operations, but they are limited in their ability to handle complex logic. When more complex logic or multiple statements are needed, it's generally better to use a regular named function defined with `def`. 

 

 

 

A truth table is a tabular representation of all possible combinations of input values for a logical expression and the corresponding output value of that expression. You can create a truth table in Python using various methods, but one common way is to use nested loops to generate the input combinations and then calculate the output based on the logical expression. 

  

Here's an example of how to create a truth table for a simple logical AND operation: 

  

```python 

# Define the logical AND function 

def logical_and(a, b): 

    return a and b 

  

# Generate and print the truth table 

print("Truth Table for Logical AND") 

print("| A | B | A AND B |") 

print("|---|---|---------|") 

for a in [True, False]: 

    for b in [True, False]: 

        result = logical_and(a, b) 

        print(f"| {int(a)} | {int(b)} |    {int(result)}    |") 

``` 

  

In this example, we have a function `logical_and` that takes two boolean values `a` and `b` and returns their logical AND result. We then use nested loops to iterate through all possible combinations of `a` and `b` (True and False), calculate the result using the `logical_and` function, and print the values in a tabular format. 

  

You can adapt this code to create truth tables for other logical operations (e.g., OR, NOT, XOR) or more complex logical expressions by defining appropriate functions and adjusting the logic accordingly. 

 

 

 

 

 

 

 

 

Day 4  

 

Operators 

 

 

In Python, you can use a variety of operators for different purposes, including arithmetic operations, comparison operations, logical operations, and more. Here's a list of common operators in Python: 

  

1. Arithmetic Operators: 

   - `+` (Addition) 

   - `-` (Subtraction) 

   - `*` (Multiplication) 

   - `/` (Division) 

   - `//` (Floor Division) 

   - `%` (Modulus/Remainder) 

   - `**` (Exponentiation) 

  

2. Comparison Operators: 

   - `==` (Equal to) 

   - `!=` (Not equal to) 

   - `<` (Less than) 

   - `>` (Greater than) 

   - `<=` (Less than or equal to) 

   - `>=` (Greater than or equal to) 

  

3. Assignment Operators: 

   - `=` (Assignment) 

   - `+=` (Add and assign) 

   - `-=` (Subtract and assign) 

   - `*=` (Multiply and assign) 

   - `/=` (Divide and assign) 

   - `//=` (Floor divide and assign) 

   - `%=` (Modulus and assign) 

   - `**=` (Exponentiate and assign) 

  

4. Logical Operators: 

   - `and` (Logical AND) 

   - `or` (Logical OR) 

   - `not` (Logical NOT) 

  

5. Bitwise Operators: 

   - `&` (Bitwise AND) 

   - `|` (Bitwise OR) 

   - `^` (Bitwise XOR) 

   - `~` (Bitwise NOT) 

   - `<<` (Left shift) 

   - `>>` (Right shift) 

  

6. Membership Operators: 

   - `in` (True if a value is found in the sequence) 

   - `not in` (True if a value is not found in the sequence) 

  

7. Identity Operators: 

   - `is` (True if two variables reference the same object) 

   - `is not` (True if two variables reference different objects) 

  

8. Ternary Operator: 

   - `x if condition else y` (Conditional expression) 

  

9. String Concatenation Operator: 

   - `+` (Used to concatenate strings) 

  

10. Slice Operator: 

    - `[start:end]` (Used to extract a portion of a sequence, such as a string or list) 

  

11. Augmented Assignment Operators: 

    - Various operators combined with `=` to perform an operation and assignment in one step, e.g., `+=`, `-=`, `*=`, etc. 

  

These operators are essential for performing different operations in Python, and they play a crucial role in expressing and manipulating data and logic in Python programs. 




 # WEEK 2 Python 
## Control Flow.
Day 1
Control flow statements.
Control flow statements in Python are used to determine the order in which a program's instructions are executed. They allow you to make decisions, create loops, and control the flow of your program.
•	Programs control flow is the order in which the programs code executes.
•	The control flow of a python program is regulated by conditional statements, loops and functions.
Python has 3 types of control structure.
•	Sequential-default mode 
•	Selection- used for decisions and branching.
•	Repetition- used for looping example repeating a piece of code multiple times.

Python provides several control flow statements, including:
1. Conditional Statements (if, elif, else):
   - `if` statement: Allows you to execute a block of code if a specified condition is true.
   - `elif` (short for "else if") statement: Used to check additional conditions if the initial `if` condition is false.
   - `else` statement: Provides a block of code to execute when the `if` and `elif` conditions are false.

Example:
```python
x = 10
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
```

2. Loops (for and while):
   - `for` loop: Iterates over a sequence (e.g., a list, tuple, string) or a range of values and executes a block of code for each element in the sequence.
   - `while` loop: Repeats a block of code if a specified condition is true.

Example (for loop):
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

Example (while loop):
```python
count = 0
while count < 5:
    print(f"Count is {count}")
    count += 1
```

3. Control Statements (break and continue):
   - `break` statement: Terminates the current loop prematurely and continues with the next code outside the loop.
   - `continue` statement: Skips the current iteration of a loop and moves on to the next iteration.

Example (break):
```python
for num in range(1, 10):
    if num == 5:
        break
    print(num)
```

Example (continue):
```python
for num in range(1, 6):
    if num == 3:
        continue
    print(num)
```

These control flow statements are fundamental for building complex programs and making decisions based on conditions or iterating through data structures. They provide the necessary flexibility to create dynamic and responsive Python programs.

Day 2
Intro to functions
In Python, a function is a reusable block of code that performs a specific task or a set of tasks. Functions are a fundamental concept in programming, as they allow you to encapsulate functionality, make your code more modular, and promote code reusability. Functions in Python are defined using the `def` keyword, followed by the function name and a set of parentheses. Here's an introduction to functions in Python:

1. Function Definition:

•	To define a function, you use the `def` keyword, followed by the function name, a set of parentheses, and a colon.
•	 The function's code block is indented beneath the definition. You can also include parameters in the parentheses if your function requires input values.

   Example of a simple function without parameters:

   ```python
   def greet():
       print("Hello, world!")
   ```

2. Function Invocation:

 To execute a function, you simply call it by its name followed by parentheses. If the function has parameters, you provide the required values within the parentheses.

   Example of calling the `greet` function:

   ```python
   greet()
   ```

3. **Return Statement**:

   Functions can return values using the `return` statement. This allows a function to produce a result that can be used in other parts of your code.

   Example of a function with a return statement:

   ```python
   def add(a, b):
       result = a + b
       return result
   ```

   You can store the returned value in a variable or use it directly:

   ```python
   sum_result = add(3, 4)
   print(sum_result)  # Outputs: 7

4. **Function Parameters**:

   Functions can take parameters (input values) to perform operations based on the provided values. You define these parameters within the function's parentheses.

   Example of a function with parameters:

   ```python
   def multiply(x, y):
       result = x * y
       return result
   ```

   Call the function with arguments:

   ```python
   product = multiply(5, 2)
   print(product)  # Outputs: 10

5. Docstrings:

 It's good practice to include a docstring (a multi-line string enclosed in triple-quotes) at the beginning of your function to provide a description of what the function does. This helps document your code and makes it easier for others (and yourself) to understand the function's purpose.

   Example with a docstring:

   ```python
   def subtract(a, b):
       """
       This function subtracts 'b' from 'a' and returns the result.
       """
       result = a - b
       return result
   ```

Functions are a powerful way to structure your code, making it more organized, readable, and maintainable. They allow you to break your program into smaller, manageable pieces that perform specific tasks, which can be called as needed. This modularity is a key aspect of writing clean and efficient Python code.

Using Functions 
•	We create functions by providing three pieces of information. The name of the function, a list of zero or more parameters, and, optionally, a block of code which provides the return value (a function can return nothing).

•	We normally define functions in script files for the simple reason that we do not want to type them more than once, we just want to edit a function (if necessary).

We must make a firm distinction between an argument value and a parameter:

·         Argument

The argument is the object used in an application of a function; it may be referenced by other variables or objects.
·         Parameter

The parameter is a variable name that is part of the function and is a local variable within the function body

We define a function by using the following syntax:
def function_name(parameter <,...>):

#suite

 There are three types of functions in Python.
•	Ordinary function 
•	Procedure function 
•	Factory functions.

•	Ordinary functions are functions that follow mathematical procedures. They will receive an argument, perform a specific calculation with the argument, and return a result.
 
•	Procedure functions normally do not return a result; they are called to execute a procedure. For example, a function can, be created to set up a connection to a database.

•	Factory functions do not take parameters. The function generates values. Some factory functions work by accessing an object encapsulated in a module. For example, you will access the random number generator encapsulated in the random module.

 The following is an example of how programs use functions to be more efficient:
def calculateTax(salary):
  """Calculates and prints a given salary’s tax"""
  if salary > 30000 :
  rate = 0.2
  elif salary > 10000 :
  rate = 0.15
  else:
  rate = 0.1
 tax = salary * rate
 print (tax)
print ("Enter the amount on which you want to calculate tax:")
calculateTax(int(input()));

The provided code defines a Python function called `calculateTax(salary)` and then demonstrates how to use this function to calculate and print the tax on a given salary. Here's a step-by-step explanation of the code:

1. `def calculateTax(salary):`:
   - This line defines a function called `calculateTax` that takes one parameter, `salary`. The parameter is enclosed in parentheses.
   - The docstring `"""Calculates and prints a given salary’s tax"""` is a comment or description of what the function does. It is good practice to include docstrings to explain the purpose of your function.

2. Inside the function, there is an if-elif-else statement:
   - `if salary > 30000:` checks if the `salary` is greater than 30,000.
   - If the condition is true, it sets the `rate` variable to 0.2, indicating a tax rate of 20%.
   - `elif salary > 10000:` checks if the salary is greater than 10,000 but not greater than 30,000.
   - If the condition is true, it sets the `rate` variable to 0.15, indicating a tax rate of 15%.
   - If neither of the above conditions is true (i.e., the salary is less than or equal to 10,000), it sets the `rate` variable to 0.1, indicating a tax rate of 10%.

3. `tax = salary * rate` calculates the tax amount by multiplying the `salary` by the determined `rate`.

4. `print(tax)` prints the calculated tax amount to the console.

5. Outside of the function, there is a `print("Enter the amount on which you want to calculate tax:")` statement, which displays a message to the user, prompting them to enter a salary amount.

6. `calculateTax(int(input()))`:
   - `input()` reads a line of text from the user (the salary amount), and `int()` converts that input to an integer. This is necessary because `input()` returns a string, and you need to perform numerical calculations on the input.
   - `calculateTax(...)` calls the `calculateTax` function, passing the entered salary as an argument.

Overall, the code defines a function to calculate and print the tax based on the given salary. It determines the tax rate based on the salary amount and then calculates the tax amount using that rate. The user is prompted to enter a salary, and the function is called with the entered salary to calculate and print the tax.

The random module
•	The basic random function generates a random floating point as output.
•	Python uses the Mersenne twister as the core generator.
•	The Mersenne Twister is an algorithm for generating random numbers. It has a very long period before its sequence of numbers will repeat (219937 – 1). It is also a very fast.
•	The functions supplied by the random module are actually bound methods of a hidden instance of the random.
The following example is an example of a function with the use of the random module:
Example 3 – Random module:
import random
def lotto_number():
  """The result from a lotto number draw is returned."""
 num = random.randrange(1,47)
 return str(num)
for n in range(1,6):
print (lotto_number())


Recursive functions

•	It’s a function that keeps calling itself until it reaches its goal.
•	In the Fibonacci sequence of numbers, each number is the sum of the previous two numbers, starting with 0 and 1. This sequence begins 0, 1, 1, 2, 3, 5, 8, 13, 21, 34…
Fibonacci recursive function:
def Fibonacci(num):
 
  if num <= 1:  # base case
   return 1
  else:
   return num * Fibonacci(num - 1) # recursive call
 
for i in range(11):
  print ("%2d = %d" % (i, Fibonacci(i)))
Output:

 0 = 1
 1 = 1
 2 = 2
 3 = 6
 4 = 24
 5 = 120
 6 = 720
 7 = 5040
 8 = 40320
 9 = 362880
10 = 3628800

A recursive function in Python is a function that calls itself, either directly or indirectly, to solve a problem by breaking it down into smaller, more manageable subproblems. It follows a concept called recursion, which is a fundamental technique in computer science and mathematics. Here's a summary of key points about recursive functions in Python:
 
1. Base Case: A recursive function must have one or more base cases. These are specific conditions that stop the recursion and provide a result without further recursive calls. Base cases prevent the function from running indefinitely.
 
2. Recursive Case: In addition to the base case, a recursive function includes one or more recursive cases. In a recursive case, the function calls itself with modified arguments, typically making the problem smaller in some way.
 
3. Example: A classic example of a recursive function is the factorial function, which calculates the factorial of a non-negative integer. The base case for the factorial function is when the input is 0, and the recursive case is to multiply the input by the factorial of (input - 1).
 
```python
def factorial(n):
    if n == 0:
        return 1  # Base case
    else:
        return n * factorial(n - 1)  # Recursive case
```
 
4. Recursion Depth: Recursive functions can lead to a call stack, and if the recursion depth becomes too deep, it may result in a "RecursionError." Python has a default recursion depth limit, which can be modified, but it's important to use recursion judiciously and ensure that it doesn't lead to excessive function calls.
 
5. Advantages and Disadvantages: Recursive functions can provide elegant and concise solutions to certain problems, making the code easier to understand and maintain. However, they may have performance overhead due to function call overhead and may be less efficient for very large inputs compared to iterative solutions.
 
6. Tail Recursion: Some programming languages offer tail call optimization, which optimizes recursive functions to avoid the accumulation of call stack frames. Python doesn't provide native tail call optimization, so large recursive functions can lead to a "RecursionError."
 
7. Indirect Recursion: In some cases, multiple functions call each other in a circular manner, which is called indirect recursion. Care must be taken to define base cases correctly in such scenarios to prevent infinite loops.
 
Recursive functions are a powerful tool in Python and can be used to solve a wide range of problems, particularly those that exhibit a recursive structure. However, it's important to use them wisely, considering the base cases, termination conditions, and potential performance implications.

Day 3 
Modules
•	A file containing python code, typically functions, classes and variables that can be imported and used in other python script.
•	Modules in Python are a fundamental concept that allows you to organize and reuse code.
•	Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.
•	Definition: A module in Python is a file containing Python code, typically functions, classes, and variables, that can be imported and used in other Python scripts. Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.
•	Usage: You can use modules to structure your code logically and make it more maintainable. Python's standard library is a collection of modules that provide a wide range of functionality, from file manipulation to web development, mathematics, and more.
•	Creating Modules: To create your own module, you can write a Python script and save it with a .py file extension. This file can contain functions, classes, and variables that you want to reuse in other parts of your program.
•	Importing Modules: To use a module in your Python script, you import it using the import statement. 
For example:
import mymodule  # Import a module named "mymodule"

•	Accessing Module Members: Once a module is imported, you can access its functions, classes, and variables using dot notation. 
For example, 
if mymodule has a function named my_function, you can call it like this:
mymodule.my_function()

•	Aliasing: You can alias a module or its members to give them shorter or more convenient names when using them in your code. 
For example:
import mymodule as mm  # Alias the module
from mymodule import my_function as mf  # Alias a specific function

•	Standard Library: Python comes with a vast standard library that includes modules for tasks like file I/O, math, networking, regular expressions, and more. These modules are readily available for use in your programs without the need for additional installation.
•	Third-Party Modules: Python's ecosystem benefits from a rich collection of third-party modules and packages that extend its capabilities. You can install and use these modules using package managers like pip.
•	Module Search Path: Python searches for modules in directories defined by the sys.path variable. By default, it includes the current directory and the standard library paths. You can add custom paths to this list to find your own modules.
•	__name__ and Module Execution: Python modules have a built-in __name__ attribute. When a module is executed, its __name__ is set to '__main__'. This allows you to include code that should only run when the module is the main program.
•	Packages: Packages are a way to organize related modules into directories and subdirectories. They include a special __init__.py file that marks a directory as a package. Packages help manage large codebases by providing a hierarchical structure.
•	Modules are a fundamental part of Python's modular and extensible design, making it easier to develop and maintain Python applications and libraries. They promote code reuse, encapsulation, and separation of concerns, making your code more organized and maintainable.


Mechanism of Python Modules


•	There's a thing called program directory where the python modules are located  its called PYTHONPATH.
Listing of Modules
•	The list of available modules in Python can be found out by executing the following command in the command prompt (interpreter shell).
When you want to see the lsit of available modules on python you execute
Help(“module”) on the console.

The mechanism of Python modules involves several steps that Python follows to locate, import, and use modules in your code. Here's a summary of the key aspects of how Python's module system works:
 
1. Module Structure: A module in Python is a file containing Python code, typically with the `.py` extension. Modules can include functions, classes, variables, and even executable code.
 
2. Module Search Path: Python uses a list of directories to search for modules. This list is defined in the `sys.path` variable and includes the following directories in this order:
   - The directory containing the script that was executed (if applicable).
   - Directories in the `PYTHONPATH` environment variable (if set).
   - Standard library directories.
   - Site-specific directories.
   - User-specific directories.
 
3. Importing Modules: To use a module in your Python script, you import it using the `import` statement. For example:
 
   ```python
   import mymodule  # Import a module named "mymodule"
   ```
 
4. Dot Notation: Once imported, you can access the functions, classes, and variables from the module using dot notation. For instance:
 
   ```python
   mymodule.my_function()
   ```
 
5. Module Caching: Python caches imported modules to improve performance. When a module is imported, it's executed only once, and subsequent imports reuse the cached module.
 
6. Module Initialization: When you import a module, Python executes the code in the module from top to bottom. However, it only does this once per module, even if the module is imported multiple times.
 
7. `__name__` Attribute: Modules have a built-in attribute called `__name__`. When a module is executed as the main program, its `__name__` is set to `'__main__'`. You can use this to include code that should only run when the module is executed directly.
 
8. Packages: Packages are a way to organize related modules into directories. A package directory includes a special `__init__.py` file, which marks it as a package. Packages help manage large codebases by providing a hierarchical structure.
 
9. Relative Imports: Modules can be organized into packages, and you can use relative imports to refer to modules within the same package. Relative imports use dot notation to specify the module's location within the package.
 
   ```python
   from . import submodule  # Relative import within a package
   ```
 
10. Standard Library and Third-Party Modules: Python's standard library provides a vast collection of modules for various tasks. In addition to the standard library, you can also install and use third-party modules and packages to extend Python's functionality.
 
Python's module mechanism is a fundamental feature of the language that promotes code organization, reusability, and maintainability. It allows you to create modular and well-structured code by separating functionality into distinct units that can be easily imported and used in your programs.


Importing modules

The syntax of importing modules for python standard path is below,
Import module_name

•	To fetch and use modules from other and new sources, we need to install Python PIP.
•	Python pip is a software that installs python modules from an index or using a manager like Anaconda.
•	Run the following command to install modules from new sources using python pip:
•	python -m pip3 install module_name
•	Run the following command to install modules from new sources using Ananconda:
•	conda install module_name
•	Example: Steps to install NumPy
•	python -m pip3 install numpy
conda install numpy
sudo apt install python3-numpy

To import modules from an external source in Python, you typically use a package manager like `pip`, which allows you to download and install packages (collections of modules) from external sources such as the Python Package Index (PyPI). Here are the steps to import modules from an external source:
 
1. **Install the Package Manager**:
   If you don't have `pip` installed, you can install it by following the instructions provided on the official Python website or the package manager's documentation.
 
2. **Search for the Desired Package**:
   Use the package manager to search for the module or package you want to import. For example, to search for a package named "requests," you can run:
 
   ```bash
   pip search requests
   ```
 
3. **Install the Package**:
   Once you've identified the package you want to use, you can install it using `pip`. For example, to install the "requests" package:
 
   ```bash
   pip install requests
   ```
 
   This command will download and install the "requests" package and its associated modules.
 
4. **Import the Module in Your Python Code**:
   After installation, you can import the module(s) in your Python code as usual. For example:
 
   ```python
   import requests
   ```
 
5. **Use the Imported Module**:
   You can then use the imported module and its functions, classes, and variables in your Python code. For example:
 
   ```python
   response = requests.get('https://www.example.com')
   ```
 
By following these steps, you can import modules from external sources in Python. The process is the same for most external packages, but you may need to consult the specific package's documentation or PyPI page for any additional installation or usage instructions. Keep in mind that using a virtual environment for your project is recommended to manage package dependencies and avoid conflicts between different projects.


Day4 

 

Regular expressions, often referred to as “regexes,” are a concise way of specifying patterns in text. They are a powerful tool in Python, thanks to the `re` module, and serve several key purposes: 

 

Parsing: Regular expressions are used to identify and extract specific pieces of text that match certain criteria within a larger text or data. 

 

Searching: They help locate substrings that may have multiple forms, such as finding various image file extensions like ‘pet.png,’ ‘pet.gif,’ and ‘pet.mpg’ while excluding ‘carpet.gif.’ 

 

 

Searching and Replacing: You can find substrings and replace specific words within the matched string or strings, such as replacing a local phone number format like ‘071 234 5678’ with an international format like ‘+2771 234 5678.’ 

 

Splitting Strings: Regular expressions are handy for splitting a string at specific delimiters. For example, you can split a comma-separated list into individual items by using a regex that matches ‘,’. 

 

 

Validation: They are used to check whether a string adheres to certain criteria, like validating whether an email address is in the standard format. 

However, regular expressions do have limitations: 

- They are suitable for handling recursive (repeating) structured text only if the maximum number of repetitions is known in advance. 

- Large and complex regex patterns can become challenging to maintain and understand. 

 

As a best practice, when dealing with highly structured data formats like XML, it’s often better to use specialized parsers tailored to that format. In simpler terms, a basic regular expression consists of a character followed by a quantifier, while more complex expressions can involve combinations of quantified expressions to match intricate patterns in text data. 

 Regular expression syntax 

This section provides an overview of regular expressions (regex) and their syntax. It covers key functions from the Python re module and presents a table of commonly used functions and their descriptions. 

 

1. **Introduction to Regular Expressions: **  

   - Regular expressions are a powerful tool for text pattern matching. 

   - The section is divided into four subsections: 

     - Matching individual characters or character groups. 

     - Quantifying matches (e.g., matching zero or more occurrences). 

     - Creating and grouping sub-expressions. 

     - Using language assertions and flags. 

 

2. **Table of re Module Functions (commonly used):** 

   - `compile`: Compiles a regex pattern. 

   - `findall`: Returns a list of all non-overlapping matches in a string. 

   - `finditer`: Returns an iterator over all matches. 

   - `match`: Tries to apply the pattern at the start of the string. 

   - `search`: Scans through a string looking for a match. 

   - `split`: Splits a string by pattern occurrences. 

   - `sub`: Replaces occurrences of the pattern in the string. 

   - `subn`: Returns a 2-tuple with the new string and the number of replacements. 

   - `template`: Compiles a template pattern. 

 

3. **Regular Expression Syntax:** 

   - This part explains various regex syntax elements: 

     - `.` (Dot): Matches any character (except newline). 

     - `^`: Matches the start of the string. 

     - `$`: Matches the end of the string. 

     - `*`: Matches zero or more occurrences. 

     - `+`: Matches one or more occurrences. 

     - `?`: Matches zero or one occurrence. 

     - `{m}`: Matches exactly m occurrences. 

     - `{m,n}`: Matches from m to n occurrences. 

     - `{m,n}?`: Matches as few occurrences as possible. 

     - `\`: Escapes special characters or signals a special sequence. 

     - `[]`: Indicates a set of characters. 

     - `|`: Represents alternation (matches X or Y). 

 

4. **Raw Strings in Python:** 

   - Explains the importance of using raw strings in regex. 

   - In raw strings, backslashes are treated as literal characters, making regex patterns cleaner. 

 

5. **Example - Validating Input Format:** 

   - Demonstrates the use of regex to validate input. 

   - Shows two equivalent regex patterns: one using a raw string and one without. 

   - Validates input in the format of three numbers enclosed in brackets. 

 

The provided code example shows how to validate input in a specific format (three numbers enclosed in brackets) using regular expressions and demonstrates the use of raw strings for cleaner pattern definition. 

 

Overall, this section provides a comprehensive introduction to regular expressions and their syntax, with a focus on Python's re module and the importance of using raw strings to simplify regex pattern creation. 

 

Character and character classes: 

In this section on regular expressions and escape characters, the following key points are discussed: 

 

1. Basic Regex Expressions: 

   - A single character, like '5' or 'b', matches one occurrence by default. 

   - Special characters in regex, like '+', '*', and '?', need a backslash (\) as a prefix if they are to be treated as literals. 

 

2. Escape Characters in Python and Regex: 

   - Escape characters in Python include '\', '\n', '\t', and more. They are used to represent special characters or control characters. 

   - To use special regex characters as literals, they must be preceded by a backslash (\). 

 

3. Example - Matching Special Characters: 

   - A Python example is given where regular expressions are used to match the presence of a '+' character and a newline character ('\n') in a sentence. 

   - The '^' symbol matches the start of the text, '.*' matches zero or more characters (including newlines), '[\+]+' matches one or more '+' characters, and '$' matches the end of the line. 

 

4. Character Classes and Ranges: 

   - Character classes, like [ea], match either 'e' or 'a'. 

   - Ranges, like [0-9], match any digit from 0 to 9. 

   - Negating a character class, like [^0-9], matches any character except digits. 

 

5. Handling Special Characters within Character Classes: 

   - Dashes (-) and some other characters are metacharacters by default. However, if they are the first character within a character class (e.g., [-abc]), they are treated as literals and do not require a backslash. 

   - Other metacharacters, like '.', '^', '?', '+', '*', are always treated as literals within character classes. 

 

6. Shortcuts in Character Classes: 

   - Python offers shortcuts for character classes, such as '\d' (matches any digit) and '\s' (matches whitespace). 

   - The ASCII flag can modify the behavior of these shortcuts. 

 

7. Example - Using Shortcuts in Character Classes: 

   - A Python example illustrates how to count the number of words in a sentence using shortcuts like '\w' and '\W'. 

   - The regular expression '^[\W]*[\w]*[\W]*' is used to identify words in a sentence. 

 

In summary, this section covers the basics of regular expressions, escape characters, character classes, and shortcuts within character classes. It provides practical examples to demonstrate the use of these concepts in Python. 

 

Quantifies and flags: 

Quantifies: 

This section explains quantifiers in regular expressions and provides shorthand notations for simplifying the use of quantifiers. The key points covered are as follows: 

 

1. Quantifiers in Regex: 

   - A quantifier in regex has the form {m, n}, specifying the minimum and maximum number of times an expression must match. 

   - For example, e{1,1}e{1,1} and e{2,2} both match "feelings" but not "belt." 

 

2. Shorthand Notations for Quantifiers: 

   - Regex provides shorthand notations to simplify quantifiers. 

   - If only one number is supplied, it's assumed that the minimum and maximum are the same. For example, e{4} is equivalent to e{4, 4}. 

   - Different minimum and maximum values can be convenient. For instance, to match both "travelled" and "traveled," you can use "travel{1,2}ed" or "travell{0,1}ed." 

   - The '?' symbol is used to represent {0,1}, meaning the preceding character is optional. 

 

3. Examples of Using Quantifiers: 

   - An example in Python demonstrates the use of quantifiers to match words like "travelled" and "traveled" with the pattern 'travell?ed' (where '?' is a shorthand for {0,1}). 

   - This allows for flexibility in matching words with different numbers of 'l' characters. 

 

In summary, this section clarifies the concept of quantifiers in regular expressions and shows how shorthand notations like '?' can be used to make regex patterns more concise and flexible. It provides a practical example in Python to illustrate the application of these quantifiers. 

 

Flags: 

Flags are used to tell the regex how to behave when looking for expressions. 

This section introduces various regex flags and their functions in Python. The key points covered include: 

 

1. Regex Flags: 

   - Python offers several flags to modify the behavior of regex patterns. 

   - Flags, like re.IGNORECASE or re.VERBOSE, can be used to make regex matching more flexible and readable. 

 

2. Examples of Flags: 

   - An example demonstrates the use of the IGNORECASE flag (re.IGNORECASE or re.I) for case-insensitive matching. It removes all vowels (both uppercase and lowercase) from a string. 

   - Another example uses the VERBOSE flag (re.VERBOSE or re.X) to make a complex regex pattern more readable. It checks whether a string is a valid octal or hexadecimal number. 

    

3. IGNORECASE Flag: 

   - The IGNORECASE flag is used to make regex matching case-insensitive, reducing the need to specify both uppercase and lowercase characters explicitly. 

 
4. VERBOSE Flag: 

   - The VERBOSE flag allows comments and white spaces to be included in a regex pattern, making complex expressions more readable. 

   - It can be especially useful for explaining longer and more intricate regular expressions. 


In summary, this section covers the use of regex flags, specifically the IGNORECASE (case-insensitive) and VERBOSE (readable) flags, and provides practical examples to illustrate their application in Python. 








 # WEEK 2 Python 
Control Flow.
## Day 1
Control flow statements.
Control flow statements in Python are used to determine the order in which a program's instructions are executed. They allow you to make decisions, create loops, and control the flow of your program.
•	Programs control flow is the order in which the programs code executes.
•	The control flow of a python program is regulated by conditional statements, loops and functions.
Python has 3 types of control structure.
•	Sequential-default mode 
•	Selection- used for decisions and branching.
•	Repetition- used for looping example repeating a piece of code multiple times.

Python provides several control flow statements, including:
1. Conditional Statements (if, elif, else):
   - `if` statement: Allows you to execute a block of code if a specified condition is true.
   - `elif` (short for "else if") statement: Used to check additional conditions if the initial `if` condition is false.
   - `else` statement: Provides a block of code to execute when the `if` and `elif` conditions are false.

Example:
```python
x = 10
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
```

2. Loops (for and while):
   - `for` loop: Iterates over a sequence (e.g., a list, tuple, string) or a range of values and executes a block of code for each element in the sequence.
   - `while` loop: Repeats a block of code if a specified condition is true.

Example (for loop):
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

Example (while loop):
```python
count = 0
while count < 5:
    print(f"Count is {count}")
    count += 1
```

3. Control Statements (break and continue):
   - `break` statement: Terminates the current loop prematurely and continues with the next code outside the loop.
   - `continue` statement: Skips the current iteration of a loop and moves on to the next iteration.

Example (break):
```python
for num in range(1, 10):
    if num == 5:
        break
    print(num)
```

Example (continue):
```python
for num in range(1, 6):
    if num == 3:
        continue
    print(num)
```

These control flow statements are fundamental for building complex programs and making decisions based on conditions or iterating through data structures. They provide the necessary flexibility to create dynamic and responsive Python programs.

Day 2
Intro to functions
In Python, a function is a reusable block of code that performs a specific task or a set of tasks. Functions are a fundamental concept in programming, as they allow you to encapsulate functionality, make your code more modular, and promote code reusability. Functions in Python are defined using the `def` keyword, followed by the function name and a set of parentheses. Here's an introduction to functions in Python:

1. Function Definition:

•	To define a function, you use the `def` keyword, followed by the function name, a set of parentheses, and a colon.
•	 The function's code block is indented beneath the definition. You can also include parameters in the parentheses if your function requires input values.

   Example of a simple function without parameters:

   ```python
   def greet():
       print("Hello, world!")
   ```

2. Function Invocation:

 To execute a function, you simply call it by its name followed by parentheses. If the function has parameters, you provide the required values within the parentheses.

   Example of calling the `greet` function:

   ```python
   greet()
   ```

3. **Return Statement**:

   Functions can return values using the `return` statement. This allows a function to produce a result that can be used in other parts of your code.

   Example of a function with a return statement:

   ```python
   def add(a, b):
       result = a + b
       return result
   ```

   You can store the returned value in a variable or use it directly:

   ```python
   sum_result = add(3, 4)
   print(sum_result)  # Outputs: 7

4. **Function Parameters**:

   Functions can take parameters (input values) to perform operations based on the provided values. You define these parameters within the function's parentheses.

   Example of a function with parameters:

   ```python
   def multiply(x, y):
       result = x * y
       return result
   ```

   Call the function with arguments:

   ```python
   product = multiply(5, 2)
   print(product)  # Outputs: 10

5. Docstrings:

 It's good practice to include a docstring (a multi-line string enclosed in triple-quotes) at the beginning of your function to provide a description of what the function does. This helps document your code and makes it easier for others (and yourself) to understand the function's purpose.

   Example with a docstring:

   ```python
   def subtract(a, b):
       """
       This function subtracts 'b' from 'a' and returns the result.
       """
       result = a - b
       return result
   ```

Functions are a powerful way to structure your code, making it more organized, readable, and maintainable. They allow you to break your program into smaller, manageable pieces that perform specific tasks, which can be called as needed. This modularity is a key aspect of writing clean and efficient Python code.

Using Functions 
•	We create functions by providing three pieces of information. The name of the function, a list of zero or more parameters, and, optionally, a block of code which provides the return value (a function can return nothing).

•	We normally define functions in script files for the simple reason that we do not want to type them more than once, we just want to edit a function (if necessary).

We must make a firm distinction between an argument value and a parameter:

·         Argument

The argument is the object used in an application of a function; it may be referenced by other variables or objects.
·         Parameter

The parameter is a variable name that is part of the function and is a local variable within the function body

We define a function by using the following syntax:
def function_name(parameter <,...>):

#suite

 There are three types of functions in Python.
•	Ordinary function 
•	Procedure function 
•	Factory functions.

•	Ordinary functions are functions that follow mathematical procedures. They will receive an argument, perform a specific calculation with the argument, and return a result.
 
•	Procedure functions normally do not return a result; they are called to execute a procedure. For example, a function can, be created to set up a connection to a database.

•	Factory functions do not take parameters. The function generates values. Some factory functions work by accessing an object encapsulated in a module. For example, you will access the random number generator encapsulated in the random module.

 The following is an example of how programs use functions to be more efficient:
def calculateTax(salary):
  """Calculates and prints a given salary’s tax"""
  if salary > 30000 :
  rate = 0.2
  elif salary > 10000 :
  rate = 0.15
  else:
  rate = 0.1
 tax = salary * rate
 print (tax)
print ("Enter the amount on which you want to calculate tax:")
calculateTax(int(input()));

The provided code defines a Python function called `calculateTax(salary)` and then demonstrates how to use this function to calculate and print the tax on a given salary. Here's a step-by-step explanation of the code:

1. `def calculateTax(salary):`:
   - This line defines a function called `calculateTax` that takes one parameter, `salary`. The parameter is enclosed in parentheses.
   - The docstring `"""Calculates and prints a given salary’s tax"""` is a comment or description of what the function does. It is good practice to include docstrings to explain the purpose of your function.

2. Inside the function, there is an if-elif-else statement:
   - `if salary > 30000:` checks if the `salary` is greater than 30,000.
   - If the condition is true, it sets the `rate` variable to 0.2, indicating a tax rate of 20%.
   - `elif salary > 10000:` checks if the salary is greater than 10,000 but not greater than 30,000.
   - If the condition is true, it sets the `rate` variable to 0.15, indicating a tax rate of 15%.
   - If neither of the above conditions is true (i.e., the salary is less than or equal to 10,000), it sets the `rate` variable to 0.1, indicating a tax rate of 10%.

3. `tax = salary * rate` calculates the tax amount by multiplying the `salary` by the determined `rate`.

4. `print(tax)` prints the calculated tax amount to the console.

5. Outside of the function, there is a `print("Enter the amount on which you want to calculate tax:")` statement, which displays a message to the user, prompting them to enter a salary amount.

6. `calculateTax(int(input()))`:
   - `input()` reads a line of text from the user (the salary amount), and `int()` converts that input to an integer. This is necessary because `input()` returns a string, and you need to perform numerical calculations on the input.
   - `calculateTax(...)` calls the `calculateTax` function, passing the entered salary as an argument.

Overall, the code defines a function to calculate and print the tax based on the given salary. It determines the tax rate based on the salary amount and then calculates the tax amount using that rate. The user is prompted to enter a salary, and the function is called with the entered salary to calculate and print the tax.

The random module
•	The basic random function generates a random floating point as output.
•	Python uses the Mersenne twister as the core generator.
•	The Mersenne Twister is an algorithm for generating random numbers. It has a very long period before its sequence of numbers will repeat (219937 – 1). It is also a very fast.
•	The functions supplied by the random module are actually bound methods of a hidden instance of the random.
The following example is an example of a function with the use of the random module:
Example 3 – Random module:
import random
def lotto_number():
  """The result from a lotto number draw is returned."""
 num = random.randrange(1,47)
 return str(num)
for n in range(1,6):
print (lotto_number())


Recursive functions

•	It’s a function that keeps calling itself until it reaches its goal.
•	In the Fibonacci sequence of numbers, each number is the sum of the previous two numbers, starting with 0 and 1. This sequence begins 0, 1, 1, 2, 3, 5, 8, 13, 21, 34…
Fibonacci recursive function:
def Fibonacci(num):
 
  if num <= 1:  # base case
   return 1
  else:
   return num * Fibonacci(num - 1) # recursive call
 
for i in range(11):
  print ("%2d = %d" % (i, Fibonacci(i)))
Output:

 0 = 1
 1 = 1
 2 = 2
 3 = 6
 4 = 24
 5 = 120
 6 = 720
 7 = 5040
 8 = 40320
 9 = 362880
10 = 3628800

A recursive function in Python is a function that calls itself, either directly or indirectly, to solve a problem by breaking it down into smaller, more manageable subproblems. It follows a concept called recursion, which is a fundamental technique in computer science and mathematics. Here's a summary of key points about recursive functions in Python:
 
1. Base Case: A recursive function must have one or more base cases. These are specific conditions that stop the recursion and provide a result without further recursive calls. Base cases prevent the function from running indefinitely.
 
2. Recursive Case: In addition to the base case, a recursive function includes one or more recursive cases. In a recursive case, the function calls itself with modified arguments, typically making the problem smaller in some way.
 
3. Example: A classic example of a recursive function is the factorial function, which calculates the factorial of a non-negative integer. The base case for the factorial function is when the input is 0, and the recursive case is to multiply the input by the factorial of (input - 1).
 
```python
def factorial(n):
    if n == 0:
        return 1  # Base case
    else:
        return n * factorial(n - 1)  # Recursive case
```
 
4. Recursion Depth: Recursive functions can lead to a call stack, and if the recursion depth becomes too deep, it may result in a "RecursionError." Python has a default recursion depth limit, which can be modified, but it's important to use recursion judiciously and ensure that it doesn't lead to excessive function calls.
 
5. Advantages and Disadvantages: Recursive functions can provide elegant and concise solutions to certain problems, making the code easier to understand and maintain. However, they may have performance overhead due to function call overhead and may be less efficient for very large inputs compared to iterative solutions.
 
6. Tail Recursion: Some programming languages offer tail call optimization, which optimizes recursive functions to avoid the accumulation of call stack frames. Python doesn't provide native tail call optimization, so large recursive functions can lead to a "RecursionError."
 
7. Indirect Recursion: In some cases, multiple functions call each other in a circular manner, which is called indirect recursion. Care must be taken to define base cases correctly in such scenarios to prevent infinite loops.
 
Recursive functions are a powerful tool in Python and can be used to solve a wide range of problems, particularly those that exhibit a recursive structure. However, it's important to use them wisely, considering the base cases, termination conditions, and potential performance implications.

Day 3 
Modules
•	A file containing python code, typically functions, classes and variables that can be imported and used in other python script.
•	Modules in Python are a fundamental concept that allows you to organize and reuse code.
•	Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.
•	Definition: A module in Python is a file containing Python code, typically functions, classes, and variables, that can be imported and used in other Python scripts. Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.
•	Usage: You can use modules to structure your code logically and make it more maintainable. Python's standard library is a collection of modules that provide a wide range of functionality, from file manipulation to web development, mathematics, and more.
•	Creating Modules: To create your own module, you can write a Python script and save it with a .py file extension. This file can contain functions, classes, and variables that you want to reuse in other parts of your program.
•	Importing Modules: To use a module in your Python script, you import it using the import statement. 
For example:
import mymodule  # Import a module named "mymodule"

•	Accessing Module Members: Once a module is imported, you can access its functions, classes, and variables using dot notation. 
For example, 
if mymodule has a function named my_function, you can call it like this:
mymodule.my_function()

•	Aliasing: You can alias a module or its members to give them shorter or more convenient names when using them in your code. 
For example:
import mymodule as mm  # Alias the module
from mymodule import my_function as mf  # Alias a specific function

•	Standard Library: Python comes with a vast standard library that includes modules for tasks like file I/O, math, networking, regular expressions, and more. These modules are readily available for use in your programs without the need for additional installation.
•	Third-Party Modules: Python's ecosystem benefits from a rich collection of third-party modules and packages that extend its capabilities. You can install and use these modules using package managers like pip.
•	Module Search Path: Python searches for modules in directories defined by the sys.path variable. By default, it includes the current directory and the standard library paths. You can add custom paths to this list to find your own modules.
•	__name__ and Module Execution: Python modules have a built-in __name__ attribute. When a module is executed, its __name__ is set to '__main__'. This allows you to include code that should only run when the module is the main program.
•	Packages: Packages are a way to organize related modules into directories and subdirectories. They include a special __init__.py file that marks a directory as a package. Packages help manage large codebases by providing a hierarchical structure.
•	Modules are a fundamental part of Python's modular and extensible design, making it easier to develop and maintain Python applications and libraries. They promote code reuse, encapsulation, and separation of concerns, making your code more organized and maintainable.


Mechanism of Python Modules


•	There's a thing called program directory where the python modules are located  its called PYTHONPATH.
Listing of Modules
•	The list of available modules in Python can be found out by executing the following command in the command prompt (interpreter shell).
When you want to see the lsit of available modules on python you execute
Help(“module”) on the console.

The mechanism of Python modules involves several steps that Python follows to locate, import, and use modules in your code. Here's a summary of the key aspects of how Python's module system works:
 
1. Module Structure: A module in Python is a file containing Python code, typically with the `.py` extension. Modules can include functions, classes, variables, and even executable code.
 
2. Module Search Path: Python uses a list of directories to search for modules. This list is defined in the `sys.path` variable and includes the following directories in this order:
   - The directory containing the script that was executed (if applicable).
   - Directories in the `PYTHONPATH` environment variable (if set).
   - Standard library directories.
   - Site-specific directories.
   - User-specific directories.
 
3. Importing Modules: To use a module in your Python script, you import it using the `import` statement. For example:
 
   ```python
   import mymodule  # Import a module named "mymodule"
   ```
 
4. Dot Notation: Once imported, you can access the functions, classes, and variables from the module using dot notation. For instance:
 
   ```python
   mymodule.my_function()
   ```
 
5. Module Caching: Python caches imported modules to improve performance. When a module is imported, it's executed only once, and subsequent imports reuse the cached module.
 
6. Module Initialization: When you import a module, Python executes the code in the module from top to bottom. However, it only does this once per module, even if the module is imported multiple times.
 
7. `__name__` Attribute: Modules have a built-in attribute called `__name__`. When a module is executed as the main program, its `__name__` is set to `'__main__'`. You can use this to include code that should only run when the module is executed directly.
 
8. Packages: Packages are a way to organize related modules into directories. A package directory includes a special `__init__.py` file, which marks it as a package. Packages help manage large codebases by providing a hierarchical structure.
 
9. Relative Imports: Modules can be organized into packages, and you can use relative imports to refer to modules within the same package. Relative imports use dot notation to specify the module's location within the package.
 
   ```python
   from . import submodule  # Relative import within a package
   ```
 
10. Standard Library and Third-Party Modules: Python's standard library provides a vast collection of modules for various tasks. In addition to the standard library, you can also install and use third-party modules and packages to extend Python's functionality.
 
Python's module mechanism is a fundamental feature of the language that promotes code organization, reusability, and maintainability. It allows you to create modular and well-structured code by separating functionality into distinct units that can be easily imported and used in your programs.


Importing modules

The syntax of importing modules for python standard path is below,
Import module_name

•	To fetch and use modules from other and new sources, we need to install Python PIP.
•	Python pip is a software that installs python modules from an index or using a manager like Anaconda.
•	Run the following command to install modules from new sources using python pip:
•	python -m pip3 install module_name
•	Run the following command to install modules from new sources using Ananconda:
•	conda install module_name
•	Example: Steps to install NumPy
•	python -m pip3 install numpy
conda install numpy
sudo apt install python3-numpy

To import modules from an external source in Python, you typically use a package manager like `pip`, which allows you to download and install packages (collections of modules) from external sources such as the Python Package Index (PyPI). Here are the steps to import modules from an external source:
 
1. **Install the Package Manager**:
   If you don't have `pip` installed, you can install it by following the instructions provided on the official Python website or the package manager's documentation.
 
2. **Search for the Desired Package**:
   Use the package manager to search for the module or package you want to import. For example, to search for a package named "requests," you can run:
 
   ```bash
   pip search requests
   ```
 
3. **Install the Package**:
   Once you've identified the package you want to use, you can install it using `pip`. For example, to install the "requests" package:
 
   ```bash
   pip install requests
   ```
 
   This command will download and install the "requests" package and its associated modules.
 
4. **Import the Module in Your Python Code**:
   After installation, you can import the module(s) in your Python code as usual. For example:
 
   ```python
   import requests
   ```
 
5. **Use the Imported Module**:
   You can then use the imported module and its functions, classes, and variables in your Python code. For example:
 
   ```python
   response = requests.get('https://www.example.com')
   ```
 
By following these steps, you can import modules from external sources in Python. The process is the same for most external packages, but you may need to consult the specific package's documentation or PyPI page for any additional installation or usage instructions. Keep in mind that using a virtual environment for your project is recommended to manage package dependencies and avoid conflicts between different projects.


Day4 

 

Regular expressions, often referred to as “regexes,” are a concise way of specifying patterns in text. They are a powerful tool in Python, thanks to the `re` module, and serve several key purposes: 

 

Parsing: Regular expressions are used to identify and extract specific pieces of text that match certain criteria within a larger text or data. 

 

Searching: They help locate substrings that may have multiple forms, such as finding various image file extensions like ‘pet.png,’ ‘pet.gif,’ and ‘pet.mpg’ while excluding ‘carpet.gif.’ 

 

 

Searching and Replacing: You can find substrings and replace specific words within the matched string or strings, such as replacing a local phone number format like ‘071 234 5678’ with an international format like ‘+2771 234 5678.’ 

 

Splitting Strings: Regular expressions are handy for splitting a string at specific delimiters. For example, you can split a comma-separated list into individual items by using a regex that matches ‘,’. 

 

 

Validation: They are used to check whether a string adheres to certain criteria, like validating whether an email address is in the standard format. 

However, regular expressions do have limitations: 

- They are suitable for handling recursive (repeating) structured text only if the maximum number of repetitions is known in advance. 

- Large and complex regex patterns can become challenging to maintain and understand. 

 

As a best practice, when dealing with highly structured data formats like XML, it’s often better to use specialized parsers tailored to that format. In simpler terms, a basic regular expression consists of a character followed by a quantifier, while more complex expressions can involve combinations of quantified expressions to match intricate patterns in text data. 

 Regular expression syntax 

This section provides an overview of regular expressions (regex) and their syntax. It covers key functions from the Python re module and presents a table of commonly used functions and their descriptions. 

 

1. **Introduction to Regular Expressions: **  

   - Regular expressions are a powerful tool for text pattern matching. 

   - The section is divided into four subsections: 

     - Matching individual characters or character groups. 

     - Quantifying matches (e.g., matching zero or more occurrences). 

     - Creating and grouping sub-expressions. 

     - Using language assertions and flags. 

 

2. **Table of re Module Functions (commonly used):** 

   - `compile`: Compiles a regex pattern. 

   - `findall`: Returns a list of all non-overlapping matches in a string. 

   - `finditer`: Returns an iterator over all matches. 

   - `match`: Tries to apply the pattern at the start of the string. 

   - `search`: Scans through a string looking for a match. 

   - `split`: Splits a string by pattern occurrences. 

   - `sub`: Replaces occurrences of the pattern in the string. 

   - `subn`: Returns a 2-tuple with the new string and the number of replacements. 

   - `template`: Compiles a template pattern. 

 

3. **Regular Expression Syntax:** 

   - This part explains various regex syntax elements: 

     - `.` (Dot): Matches any character (except newline). 

     - `^`: Matches the start of the string. 

     - `$`: Matches the end of the string. 

     - `*`: Matches zero or more occurrences. 

     - `+`: Matches one or more occurrences. 

     - `?`: Matches zero or one occurrence. 

     - `{m}`: Matches exactly m occurrences. 

     - `{m,n}`: Matches from m to n occurrences. 

     - `{m,n}?`: Matches as few occurrences as possible. 

     - `\`: Escapes special characters or signals a special sequence. 

     - `[]`: Indicates a set of characters. 

     - `|`: Represents alternation (matches X or Y). 

 

4. **Raw Strings in Python:** 

   - Explains the importance of using raw strings in regex. 

   - In raw strings, backslashes are treated as literal characters, making regex patterns cleaner. 

 

5. **Example - Validating Input Format:** 

   - Demonstrates the use of regex to validate input. 

   - Shows two equivalent regex patterns: one using a raw string and one without. 

   - Validates input in the format of three numbers enclosed in brackets. 

 

The provided code example shows how to validate input in a specific format (three numbers enclosed in brackets) using regular expressions and demonstrates the use of raw strings for cleaner pattern definition. 

 

Overall, this section provides a comprehensive introduction to regular expressions and their syntax, with a focus on Python's re module and the importance of using raw strings to simplify regex pattern creation. 

 

Character and character classes: 

In this section on regular expressions and escape characters, the following key points are discussed: 

 

1. Basic Regex Expressions: 

   - A single character, like '5' or 'b', matches one occurrence by default. 

   - Special characters in regex, like '+', '*', and '?', need a backslash (\) as a prefix if they are to be treated as literals. 

 

2. Escape Characters in Python and Regex: 

   - Escape characters in Python include '\', '\n', '\t', and more. They are used to represent special characters or control characters. 

   - To use special regex characters as literals, they must be preceded by a backslash (\). 

 

3. Example - Matching Special Characters: 

   - A Python example is given where regular expressions are used to match the presence of a '+' character and a newline character ('\n') in a sentence. 

   - The '^' symbol matches the start of the text, '.*' matches zero or more characters (including newlines), '[\+]+' matches one or more '+' characters, and '$' matches the end of the line. 

 

4. Character Classes and Ranges: 

   - Character classes, like [ea], match either 'e' or 'a'. 

   - Ranges, like [0-9], match any digit from 0 to 9. 

   - Negating a character class, like [^0-9], matches any character except digits. 

 

5. Handling Special Characters within Character Classes: 

   - Dashes (-) and some other characters are metacharacters by default. However, if they are the first character within a character class (e.g., [-abc]), they are treated as literals and do not require a backslash. 

   - Other metacharacters, like '.', '^', '?', '+', '*', are always treated as literals within character classes. 

 

6. Shortcuts in Character Classes: 

   - Python offers shortcuts for character classes, such as '\d' (matches any digit) and '\s' (matches whitespace). 

   - The ASCII flag can modify the behavior of these shortcuts. 

 

7. Example - Using Shortcuts in Character Classes: 

   - A Python example illustrates how to count the number of words in a sentence using shortcuts like '\w' and '\W'. 

   - The regular expression '^[\W]*[\w]*[\W]*' is used to identify words in a sentence. 

 

In summary, this section covers the basics of regular expressions, escape characters, character classes, and shortcuts within character classes. It provides practical examples to demonstrate the use of these concepts in Python. 

 

Quantifies and flags: 

Quantifies: 

This section explains quantifiers in regular expressions and provides shorthand notations for simplifying the use of quantifiers. The key points covered are as follows: 

 

1. Quantifiers in Regex: 

   - A quantifier in regex has the form {m, n}, specifying the minimum and maximum number of times an expression must match. 

   - For example, e{1,1}e{1,1} and e{2,2} both match "feelings" but not "belt." 

 

2. Shorthand Notations for Quantifiers: 

   - Regex provides shorthand notations to simplify quantifiers. 

   - If only one number is supplied, it's assumed that the minimum and maximum are the same. For example, e{4} is equivalent to e{4, 4}. 

   - Different minimum and maximum values can be convenient. For instance, to match both "travelled" and "traveled," you can use "travel{1,2}ed" or "travell{0,1}ed." 

   - The '?' symbol is used to represent {0,1}, meaning the preceding character is optional. 

 

3. Examples of Using Quantifiers: 

   - An example in Python demonstrates the use of quantifiers to match words like "travelled" and "traveled" with the pattern 'travell?ed' (where '?' is a shorthand for {0,1}). 

   - This allows for flexibility in matching words with different numbers of 'l' characters. 

 

In summary, this section clarifies the concept of quantifiers in regular expressions and shows how shorthand notations like '?' can be used to make regex patterns more concise and flexible. It provides a practical example in Python to illustrate the application of these quantifiers. 

 

Flags: 

Flags are used to tell the regex how to behave when looking for expressions. 

This section introduces various regex flags and their functions in Python. The key points covered include: 

 

1. Regex Flags: 

   - Python offers several flags to modify the behavior of regex patterns. 

   - Flags, like re.IGNORECASE or re.VERBOSE, can be used to make regex matching more flexible and readable. 

 

2. Examples of Flags: 

   - An example demonstrates the use of the IGNORECASE flag (re.IGNORECASE or re.I) for case-insensitive matching. It removes all vowels (both uppercase and lowercase) from a string. 

   - Another example uses the VERBOSE flag (re.VERBOSE or re.X) to make a complex regex pattern more readable. It checks whether a string is a valid octal or hexadecimal number. 

    

3. IGNORECASE Flag: 

   - The IGNORECASE flag is used to make regex matching case-insensitive, reducing the need to specify both uppercase and lowercase characters explicitly. 
 
4. VERBOSE Flag: 

   - The VERBOSE flag allows comments and white spaces to be included in a regex pattern, making complex expressions more readable. 

   - It can be especially useful for explaining longer and more intricate regular expressions. 


 this section covers the use of regex flags, specifically the IGNORECASE (case-insensitive) and VERBOSE (readable) flags, and provides practical examples to illustrate their application in Python. 

# Week 3 Python
## Data structure 
### Day 1
•	.Function Definition:
o	`fib(n)` is defined to print the Fibonacci series up to the given boundary `n`.
o	`fib2(n)` is defined to return a list containing the Fibonacci series up to `n`.

•	Fibonacci Calculation:
o	The Fibonacci series is generated using two variables, `a` and `b`, initialized to 0 and 1.
o	The series is calculated in a loop using the formula `a, b = b, a + b`.

•	Printing vs. Returning:
o	`fib(n)` prints the series while `fib2(n)` returns it as a list.
•	Function Calls:
o	`fib(2000)` and `fib(0)` are examples of function calls.
o	`fib2(100)` returns the Fibonacci series up to 100 and stores it in the variable `f100`.

•	Return Statement:
o	The `return` statement is used to return a value from a function. It returns `None` if omitted.

•	List Manipulation:
o	`result.append(a)` adds the value of `a` to the `result` list.

•	Method Calls:
o	`result.append(a)` demonstrates calling a method (`append()`) on a list object (`result`).
•	Function Renaming:
o	Functions can be assigned to other names, like `f = fib`, allowing you to call them using the new name.

•	None:
o	Functions without a `return` statement return `None`. It's Python's way of representing no value.

•	Efficiency:
o	The `result.append(a)` method is more efficient than `result = result + [a]` for building lists.

More on lists:
•	`list.append(x)`: Add an item to the end of the list.
•	`list.extend(iterable)`: Extend the list by appending items from an iterable.
•	`list.insert(i, x)`: Insert an item at a given position.
•	`list.remove(x)`: Remove the first occurrence of an item with a specific value.
•	`list.pop([i])`: Remove and return an item at a given position or the last item if no index is specified.
•	`list.clear()`: Remove all items from the list.
•	`list.index(x)`: Find the index of the first item with a specific value.
•	`list.count(x)`: Count the number of times a specific value appears in the list.
•	`list.sort()`: Sort the list in place.
•	`list.reverse()`: Reverse the list in place.
•	`list.copy()`: Create a shallow copy of the list.

These methods allow you to manipulate and work with lists efficiently.
Using List as stack and queues:
You can use a list as a stack for "last-in, first-out" operations by using `append()` to add items to the top and `pop()` to retrieve items from the top.

For a queue with "first-in, first-out" operations, it's better to use `collections.deque` for efficiency. It provides fast appends and pops from both ends.

Stack using list:
 

Queue using collections.deque:
 

Lists are not efficient for queues because inserting or popping from the beginning of a list is slow due to shifting elements. Use `collections.deque` for faster queue operations.
List comprehensions:

List comprehension provides a concise way to create lists in Python. They consist of an expression followed by a for clause and optional if.


 

 

 
 

 

 

Nested List Comprehensions:
You can use list comprehensions for complex tasks, like transposing a matrix, but prefer built-in functions when possible. For transposing, use zip():

 

The del statement / Tuples and Sequences:
In Python, you can use the del statement to remove items from a list by specifying their index or clear the entire list. For example:
 
•	Tuples are similar to lists but are immutable, meaning you can't change their elements after creation. They are often used for different purposes. 
•	Tuples are defined with parentheses, and they can be nested. You can use sequence unpacking to assign values from a tuple to variables:
 
•	Tuples with one item require a trailing comma to distinguish them from parentheses, like this:
 
•	Tuples are useful for situations where you want to ensure data remains unchanged, and sequence unpacking simplifies variable assignment from tuples.
Sets:
	Python has a set data type that stores an unordered collection of unique elements.
	You can create a set using curly braces or the set () function.
	Sets are handy for membership testing and mathematical operations like union, intersection, difference, and symmetric difference.
 

 

 
Dictionaries:
•	Dictionaries are another data type in Python, used for key-value pairs. 
•	Dictionaries are created with curly braces or the dict() constructor. 
•	Keys must be unique, and you can store, extract, or delete values based on keys. Here's a quick overview.

 

 
 

Looping Techniques:
You can loop through dictionaries using the items () method to get both the key and value simultaneously:
 

You can loop through sequences and get the index and value using enumerate():
 
To loop over multiple sequences in parallel, use zip():
 
For looping in reverse, use reversed():
 
To loop over a sequence in sorted order, use sorted():
 
Avoid modifying a list while looping over it, and consider creating a new list instead. For example, you can filter out NaN values from a list:
 

Comparing Sequences and Other Types:
•	Sequence objects can be compared to other objects of the same type using lexicographical ordering. This means they are compared element by element, with the first differing element determining the outcome.
•	If all elements are equal, the sequences are considered equal.

Examples of comparisons:
o	(1, 2, 3) < (1, 2, 4)
o	[1, 2, 3] < [1, 2, 4]
o	'ABC' < 'C' < 'Pascal' < 'Python'
o	(1, 2, 3, 4) < (1, 2, 4)
o	(1, 2) < (1, 2, -1)
o	(1, 2, 3) == (1.0, 2.0, 3.0)
o	(1, 2, ('aa', 'ab')) < (1, 2, ('abc', 'a'), 4)

You can compare objects of different types if they have appropriate comparison methods. Otherwise, it raises a TypeError exception.

Day 2:
How to create list.
A Python list is like a container that can hold multiple items (numbers, words, etc.). To create a list, you put your items inside square brackets [ ], separated by commas.
 
We can also have nested list, which we can have list as items:
 

Access list elements:
•	In Python, you can access elements in a list using the index operator [].
•	Lists start with an index of 0, so the first item is at index 0, the second at 1, and so on. For example
•	We can use the index operator [] to access an item in a list. In Python, indices start at 0. So, a list having 5 elements will have an index from 0 to 4.
•	Trying to access indexes other than these will raise an IndexError. The index must be an integer. We can't use float or other types, this will result in TypeError.
•	Nested lists are accessed using nested indexing.

 
Output:
 

Negative indexing:
In Python, you can use negative indexing to access items in a list or sequence.

•	Index -1 refers to the last item.
•	Index -2 refers to the second-to-last item.
•	And so on, with each negative index counting backward from the end of the list.
 
Output:
 
How to slice lists in Python?

 

Output:
 












Add/Change List Elements:
•	Lists are mutable, meaning their elements can be changed unlike stings or tuple.
•	We can use the assignment operator = to change an item or range of items.
 

Output.
 


•	We can add an item on the list using append ().
•	Add several items using extend().
    

•	Use the + operator to combine two lists.
•	This is called concatenation.
•	The * operator repeats a list for the given number of times.
 


Delete/Remove List Elements
•	In Python, you can delete or remove elements from a list using various methods. 
•	The two primary methods for removing elements from a list are using the `del` statement and the `remove()` method. 
Here's a summary of each method along with an example:

•	Using the `del` Statement:
-	The `del` statement allows you to remove an element from a list by specifying its index.
-	It can also be used to delete entire slices of a list.
-	This method directly modifies the original list.

Example:
•	```python
•	# Create a list
•	my_list = [1, 2, 3, 4, 5]

•	# Remove the element at index 2 (which is '3')
•	del my_list[2]

•	print(my_list)  # Output: [1, 2, 4, 5]
```

•	Using the `remove()` Method:
-	The `remove()` method is used to delete the first occurrence of a specific value from the list.
-	It does not require specifying an index but rather the actual value to be removed.
-	If the value appears multiple times in the list, only the first occurrence is removed.

Example:
•	```python
•	# Create a list
•	my_list = [1, 2, 3, 2, 4, 5]

•	# Remove the first occurrence of the value '2'
•	my_list.remove(2)

•	print(my_list)  # Output: [1, 3, 2, 4, 5]
•	```

•	It's important to note that if you want to remove an element from a list without knowing its index or value, you can use methods like `pop()` to remove the last element, or you can use list slicing to create a new list with the elements you want to keep. Additionally, you can use list comprehensions to filter out specific elements from a list and create a new list without them.

Python List Method
Python provides a variety of built-in list methods that allow you to manipulate and perform operations on lists efficiently. Here's a summary of some commonly used Python list methods along with examples:

1. **append(element):**
   - The `append()` method is used to add an element to the end of a list.

   **Example:**
   ```python
   my_list = [1, 2, 3]
   my_list.append(4)
   print(my_list)  # Output: [1, 2, 3, 4]
   ```

2. **extend(iterable):**
   - The `extend()` method is used to add elements from an iterable (e.g., another list) to the end of the list.

   **Example:**
   ```python
   my_list = [1, 2, 3]
   my_list.extend([4, 5])
   print(my_list)  # Output: [1, 2, 3, 4, 5]
   ```

3. **insert(index, element):**
   - The `insert()` method allows you to insert an element at a specified index in the list.

   **Example:**
   ```python
   my_list = [1, 2, 3]
   my_list.insert(1, 4)
   print(my_list)  # Output: [1, 4, 2, 3]
   ```

4. **remove(element):**
   - The `remove()` method deletes the first occurrence of a specific element in the list.

   **Example:**
   ```python
   my_list = [1, 2, 3, 2, 4, 5]
   my_list.remove(2)
   print(my_list)  # Output: [1, 3, 2, 4, 5]
   ```

5. pop([index]):
   - The `pop()` method removes and returns the element at the specified index. If no index is provided, it removes and returns the last element.

   Example:
   ```python
   my_list = [1, 2, 3, 4]
   popped_element = my_list.pop(2)
   print(popped_element)  # Output: 3
   print(my_list)         # Output: [1, 2, 4]
   ```

6. **index(element):**
   - The `index()` method returns the index of the first occurrence of a specified element.

   **Example:**
   ```python
   my_list = [10, 20, 30, 20, 40]
   index = my_list.index(20)
   print(index)  # Output: 1
   ```

7. **count(element):**
   - The `count()` method returns the number of times a specific element appears in the list.

   **Example:**
   ```python
   my_list = [1, 2, 2, 3, 2, 4, 5]
   count = my_list.count(2)
   print(count)  # Output: 3
These are just a few of the many list methods available in Python for various list operations. Understanding and using these methods can greatly simplify list manipulation and make your code more efficient.

Day 3 
Errors and Exceptions.
•	In Python, errors and exceptions are part of the debugging landscape. 
•	Errors are issues that prevent the interpreter from running the program, while exceptions are raised during the program's execution.
•	Common types of errors include syntax errors, which occur when the code doesn't adhere to the language's rules, and runtime errors, which happen during program execution. 
•	Exceptions, on the other hand, are events that occur during runtime but don't necessarily lead to a program crash.
Syntax Errors.
•	These are the most common complains you get while you are still learning python.
 
Exceptions 
•	Errors detected during execution are called exceptions and are not unconditionally fatal.

Example 
 
•	The last line of the error message indicates what happened.
•	 Exceptions come in different types, and the type is printed as part of the message: the types in the example are ZeroDivisionError, NameError and TypeError. 
•	The string printed as the exception type is the name of the built-in exception that occurred. 
•	This is true for all built-in exceptions but need not be true for user-defined exceptions (although it is a useful convention).
•	 Standard exception names are built-in identifiers (not reserved keywords).
•	The rest of the line provides detail based on the type of exception and what caused it.
•	The preceding part of the error message shows the context where the exception occurred, in the form of a stack traceback. 
•	In general, it contains a stack traceback listing source lines; however, it will not display lines read from standard input.
•	Built-in Exceptions lists the built-in exceptions and their meanings.
        
Handling Exceptions                              
•	To handle exceptions, Python provides a try-except block Code within the try block is executed, and if an exception occurs, the corresponding except block is triggered. 
•	This allows for graceful error handling and prevents your program from abruptly terminating.
•	It’s possible to write programs that handles exceptions.

 

Python also supports raising exceptions manually using the raise keyword. This can be useful for signaling specific conditions that should be handled by the calling code.

Understanding and effectively handling errors and exceptions is crucial for writing robust and reliable Python code.


Syntax Error:
python
# Syntax Error
print("Hello, world!"
```
Here, the missing closing parenthesis will raise a syntax error.
Runtime Error:
python
# Runtime Error
result = 10 / 0

This will result in a `ZeroDivisionError` during program execution.

Handling Exceptions:
python
# Handling Exceptions
try:
    x = int(input("Enter a number: "))
    result = 10 / x
    print("Result:", result)
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Invalid input. Please enter a number.")

This code attempts to take user input, convert it to an integer, and then perform a division. If the user enters zero or a non-numeric value, it catches the corresponding exceptions.

Raising Exceptions:
python
# Raising Exceptions
def validate_age(age):
    if age < 0:
        raise ValueError("Age cannot be negative.")

try:
    user_age = int(input("Enter your age: "))
    validate_age(user_age)
    print("Valid age!")
except ValueError as ve:
    print(f"Error: {ve}")

In this example, the `validate_age` function raises a `ValueError` if the age is negative. The main code then catches and handles this exception.

These examples illustrate how errors and exceptions work in Python, along with the use of try-except blocks and manual exception raising.

Raising an Exception
Raising an exception in Python involves using the `raise` keyword to signal that a specific error or exceptional condition has occurred during the program's execution. This can be useful for indicating problems or enforcing certain conditions in your code.


1. Syntax:
   ```python
   raise ExceptionType("Error message")
   ```

2. Custom Exceptions:
   You can create your own exception classes by inheriting from the `Exception` class or one of its subclasses.

   ```python
   class CustomError(Exception):
       pass

   # Raise custom exception
   raise CustomError("This is a custom error.")
   ```

3. Raising Built-in Exceptions:
   You can raise built-in exceptions with specific error messages to convey information about the problem.

   python
   raise ValueError("Invalid input. Please enter a positive number.")
   

4. Conditional Raising:
   You can use conditional statements to raise exceptions based on certain conditions.

   ```python
   x = -5
   if x < 0:
       raise ValueError("Value must be non-negative.")
   ```

5. Handling Raised Exceptions:
   It's important to use try-except blocks to catch and handle exceptions appropriately. This prevents the program from crashing and allows for controlled error management.

   ```python
   try:
       # code that may raise an exception
   except CustomError as ce:
       print(f"Caught a custom exception: {ce}")
   except Exception as e:
       print(f"Caught a general exception: {e}")

Raising exceptions

•	is a powerful mechanism for signaling exceptional conditions in your code and providing meaningful error messages for debugging and user feedback.
•	Raising an exception in Python involves using the `raise` keyword to deliberately generate an error or signal a specific condition. Here's a concise summary:

1. Basic Syntax:
   - Use the `raise` keyword followed by the type of exception you want to raise.
   - Optionally, provide an error message to provide more context.

   ```python
   raise ValueError("This is a custom error message.")
   ```

2. **Custom Exceptions:**
   - You can create your own exception classes by inheriting from built-in exception classes or the base `Exception` class.

   ```python
   class CustomError(Exception):
       pass

   raise CustomError("Custom error message.")
   ```

3. **Conditional Raising:**
   - You can use conditional statements to decide when to raise an exception.

   ```python
   x = -5
   if x < 0:
       raise ValueError("Value must be non-negative.")
   ```

4. **Handling Raised Exceptions:**
   - Use try-except blocks to catch and handle exceptions.
   - This prevents the program from crashing and allows for graceful error handling.

   ```python
   try:
       # code that may raise an exception
   except CustomError as ce:
       print(f"Caught a custom exception: {ce}")
   except Exception as e:
       print(f"Caught a general exception: {e}")
   ```
Raising exceptions is a controlled way to handle errors in your code, providing a mechanism for communicating issues and enabling proper error management.

Explaining exceptions
 in Python involves understanding how the language deals with errors during program execution. 

Here's a brief summary:

1. **Types of Errors:**
   - **Syntax Errors:** Detected by the interpreter during the parsing of the code. They prevent the program from running.
   - **Runtime Errors (Exceptions):** Occur during the execution of the program, leading to its interruption.

2. **Exception Handling:**
   - Python uses a try-except block for handling exceptions.
   - Code within the try block is executed, and if an exception occurs, the corresponding except block is triggered.

3. **Common Exceptions:**
   - Examples include `TypeError`, `ValueError`, `ZeroDivisionError`, and more.
   - Each exception type corresponds to a specific error scenario.

4. **Custom Exceptions:**
   - Developers can create custom exception classes by inheriting from built-in exception classes or the base `Exception` class.

   ```python
   class CustomError(Exception):
       pass
   ```

5. **Raising Exceptions:**
   - Developers can manually raise exceptions using the `raise` keyword.
   - This is useful for signaling specific conditions or errors within the code.

   ```python
   raise ValueError("Invalid input.")
   ```

6. **Exception Hierarchy:**
   - Exceptions are organized in a hierarchy, with the base class being `BaseException`.
   - Specific exception classes inherit from more general ones.

7. **Finally Block:**
   - The `finally` block, if included, is executed regardless of whether an exception is raised or not. It's often used for cleanup operations.

   ```python
   try:
       # code that may raise an exception
   except SomeException:
       # handle specific exception
   finally:
       # code that will always run
   ```

Understanding exceptions is crucial for writing robust code, as it allows for controlled error handling and ensures that unexpected issues don't lead to program crashes.
Day4
Classes
In Python, classes serve as blueprints for creating objects, instances of the class. They enable the bundling of data (attributes) and functionality (methods). Here's a concise overview:

- **Defining a Class:**
  - Use the `class` keyword followed by the class name and a colon.
  - Class names are conventionally written in CamelCase.

  ```python
  class MyClass:
      def __init__(self, var1, var2):
          self.var1 = var1
          self.var2 = var2
  ```

- **Class Methods:**
  - Methods are functions defined within a class, operating on the class's data.

  ```python
  class MyClass:
      def __init__(self, var1, var2):
          self.var1 = var1
          self.var2 = var2

      def display_vars(self):
          print("Var1:", self.var1)
          print("Var2:", self.var2)
  ```

- **Creating an Object:**
  - Instantiate a class to create an object.
  - Call methods on the object.

  ```python
  obj = MyClass(10, 20)
  obj.display_vars()
  ```

- **Inheritance:**
  - Allows a class (subclass) to inherit properties and methods from another class (superclass).

  ```python
  class ParentClass:
      def __init__(self, var1, var2):
          self.var1 = var1
          self.var2 = var2

  class ChildClass(ParentClass):
      def __init__(self, var1, var2, var3):
          super().__init__(var1, var2)
          self.var3 = var3
  ```

- **Principles of OOP:**
  - **Encapsulation:** Bundling data and methods into a class, controlling access through public methods. Use underscores for private and protected attributes.

    ```python
    class MyClass:
        def __init__(self):
            self._protected_var = 10  # protected variable
            self.__private_var = 20  # private variable

        def get_private_var(self):
            return self.__private_var
    ```

  - **Abstraction:** Hiding complex implementation details, often achieved through abstract classes and interfaces.

    ```python
    from abc import ABC, abstractmethod

    class Shape(ABC):
        @abstractmethod
        def area(self):
            pass

    class Square(Shape):
        def __init__(self, side):
            self.side = side

        def area(self):
            return self.side * self.side
    ```

  - **Polymorphism:** Objects of different classes treated as objects of a common superclass, achieved through method overriding.

    ```python
    class Animal:
        def sound(self):
            pass

    class Dog(Animal):
        def sound(self):
            return "Woof!"

    class Cat(Animal):
        def sound(self):
            return "Meow!"

    def print_animal_sound(animal):
        print(animal.sound())

    dog = Dog()
    cat = Cat()

    print_animal_sound(dog)
    print_animal_sound(cat)
    ```

These principles promote organized, efficient, and maintainable Python code. Additionally, Python's approach to namespaces and scopes enhances code clarity, and the proper use of class and instance variables contributes to effective object-oriented programming.









 
