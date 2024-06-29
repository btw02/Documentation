### 1. Do pobrania od użytkownika tekstu z klawiatury służy

- **TLDR:** input()
- **Detailed Answer:** In Python, to get input from the user through the keyboard, you use the input() function. This function reads a line from input, converts it to a string (stripping a trailing newline), and returns that.

```
user_input = input("Enter some text: ")
print("You entered:", user_input)
```
---
### 2. Co wyświetli linijka: print(3"Hard")*

- **TLDR:** HardHardHard
- **Detailed Answer:** The statement print(3 * "Hard") will output HardHardHard. In Python, multiplying a string by an integer n results in that string being repeated n times. Thus, "Hard" repeated 3 times is "HardHardHard".
---
### 3. "123" to

- **TLDR:** A string
- **Detailed Answer:** "123" is a string in Python. Strings are sequences of characters enclosed in quotation marks. Even though "123" consists of digits, it's treated as a text string rather than a numeric value.
---
### 4. Jaką wartość ma wyrażenie: 1+2+3 > 5

- **TLDR:** True
- **Detailed Answer:** The expression 1 + 2 + 3 > 5 evaluates to True. Here’s why:
First, the addition is performed: 1 + 2 + 3 = 6
Then, the comparison is made: 6 > 5
Since 6 is greater than 5, the expression evaluates to True.
---
### 5. Co zawsze musi się znaleźć w kodzie przed użyciem else

- **TLDR:** An if statement
- **Detailed Answer:** An else statement must always be preceded by an if statement. The else part is used to execute code when the condition in the if statement is false.
```
if condition:
    # code to execute if condition is True
else:
    # code to execute if condition is False
```
---
### 6. Komentarz w Pythonie rozpoczynamy znakiem

- **TLDR:** #
- **Detailed Answer:** In Python, comments are initiated with the hash character #. Anything written after the # on the same line is ignored by the Python interpreter.
```
# This is a comment
print("Hello, World!")  # This is also a comment
```
---
### 7. Pętla for w Pythonie iteruje po

- **TLDR:** An iterable (e.g., list, tuple, string)
- **Detailed Answer:** A for loop in Python iterates over any iterable object, such as lists, tuples, strings, or ranges.

```
for item in [1, 2, 3]:
    print(item)
# This will print: 1, 2, 3 each on a new line
```
---
### 8. Jeśli x = [1,2,3] to x[-2] wynosi

- **TLDR:** 2
- **Detailed Answer:** In Python, negative indexing allows you to access elements from the end of a list. If x = [1, 2, 3], then x[-2] accesses the second-to-last element, which is 2.
---
### 9. Linijka a = {} będzie oznaczać

- **TLDR:** An empty dictionary
- **Detailed Answer:** The line a = {} creates an empty dictionary in Python. Dictionaries are collections of key-value pairs. At this point, a is an empty dictionary with no keys or values.
---
### 10. Co przedstawia zapis: while -5: print("nic")

- **TLDR:** An infinite loop that prints "nic"
- **Detailed Answer:** The while loop continues as long as the condition is true. In Python, any non-zero number (including negative numbers) is considered True. Therefore, while -5 will result in an infinite loop printing "nic".
---
### 11. Znakiem dziesiętnym dla liczb w języku Python jest

- **TLDR:** . (dot)
- **Detailed Answer:** In Python, the decimal point for floating-point numbers is represented by a dot .. For example, 3.14 is a floating-point number.
---
### 12. Czego NIE możemy użyć do dodania nowej wartości do listy?

TLDR: add()
Detailed Answer: To add new values to a list in Python, you can use methods like append(), extend(), or the += operator. The method add() is not applicable to lists; it's used with sets.

```my_list = [1, 2, 3]
my_list.append(4)  # Correct
```
---
### 13. my_set = (22,55,66) to:

- **TLDR:** A tuple
- **Detailed Answer:** The expression my_set = (22, 55, 66) defines a tuple, not a set. Tuples are immutable sequences, typically used to store collections of heterogeneous data. Sets, on the other hand, are defined using curly braces {}.
------
### 14. Które z podanych słów nie jest słowem kluczowym w Pythonie?

- **TLDR:** This is context-dependent
- **Detailed Answer:** Without the specific list of words, it’s not possible to determine the non-keyword. Python keywords include if, else, for, while, break, etc. You can check all keywords using
```
import keyword
print(keyword.kwlist)
```
---
### 15. Instrukcja continue pozwala na

- **TLDR:** Skipping the rest of the current loop iteration
- **Detailed Answer:** The continue statement in Python is used inside loops to skip the rest of the code inside the current iteration and immediately move to the next iteration of the loop.

```
for i in range(5):
    if i == 2:
        continue
    print(i)
# This will print: 0, 1, 3, 4 (skips 2)
```

---
### 16. Pętla: while False: print("nic")

- **TLDR:** Does not execute
- **Detailed Answer:** The while False loop will never execute its body because the condition is always false. Thus, print("nic") will never be executed.
---
### 17. Generator range(2,8)

- **TLDR:** Generates numbers from 2 to 7
- **Detailed Answer:** The range(2, 8) function generates a sequence of numbers starting from 2 up to, but not including, 8. This means it will produce the numbers 2, 3, 4, 5, 6, and 7.
---

### 18. Domyślny krok (skok) w generatorze range ma wartość

- **TLDR:** 1
- **Detailed Answer:** The default step in the range function is 1. If you don't specify the step, it will increment by 1. For example, range(3) generates 0, 1, 2.
---

### 19. Jaki jest cel zastosowania parametrów domyślnych w definicji funkcji?

- **TLDR:** To allow function calls with fewer arguments
- **Detailed Answer:** Default parameters in function definitions provide default values for arguments, enabling the function to be called with fewer arguments than it is defined with.

```
def greet(name="World"):
    print("Hello, " + name)
greet()  # Output: Hello, World
greet("Alice")  # Output: Hello, Alice
```
---

### 20. Co wyświetli się w wyniku wywołania: print(11,12,"tak")

- **TLDR:** 11 12 tak
- **Detailed Answer:** The print(11, 12, "tak") function will output 11 12 tak. By default, print separates its arguments by a space.
---

### 21. Zmienna lokalna

- **TLDR:** A variable defined within a function
- **Detailed Answer:** A local variable is one that is defined within a function and can only be used inside that function. It is not accessible outside the function.
```
def my_function():
    local_var = 10
    print(local_var)
my_function()  # Output: 10
# print(local_var)  # This will cause an error since local_var is not defined outside my_function
```
---
### 22. Słowa kluczowe w języku Python możemy zobaczyć, korzystając z modułu

- **TLDR:** keyword
- **Detailed Answer:** Python's keyword module can be used to see all the keywords. You can get the list of keywords using:
```
import keyword
print(keyword.kwlist)
```
---
### 23. random.choice(ARRAY) zwraca

- **TLDR:** A random element from the array
- **Detailed Answer:** The random.choice(ARRAY) function returns a randomly selected element from a non-empty sequence like a list.

```
import random
my_list = [1, 2, 3, 4, 5]
print(random.choice(my_list))  # Could print any number from the list
```
---
### 24. Ile linijek wyświetli się w wyniku wywołania: print("pierwsza\n"); print("druga")

- **TLDR:** Two lines
- **Detailed Answer:** The code print("pierwsza\n"); print("druga") will print two lines. The first print statement outputs pierwsza followed by a newline, and the second print statement outputs druga.
---
### 25. Która z poniższych wartości jest logicznym False?

- **TLDR:** Common false values include None, 0, 0.0, '', [], (), {}
- **Detailed Answer:** In Python, the following are considered logically False: None, False, 0, 0.0, '' (empty string), [] (empty list), () (empty tuple), and {} (empty dictionary).
---
### 26. Metoda w klasie to:

- **TLDR:** A function defined inside a class
- **Detailed Answer:** A method in a class is a function that is defined within a class body and intended to operate on instances of that class.
```
class MyClass:
    def my_method(self):
        print("Hello, world!")
```
---
### 27. Który z poniższych zapisów oznacza, że klasa A dziedziczy pola i metody po klasie B?

- **TLDR:** class A(B):
- **Detailed Answer:** The syntax class A(B): indicates that class A inherits from class B. This means A will inherit all attributes and methods from B.
---
### 28. Pętle w Pythonie to

- **TLDR:** for and while
- **Detailed Answer:** Python supports for and while loops for iteration. A for loop iterates over items of any sequence (e.g., a list or a string), while a while loop repeatedly executes a block of statements as long as a given condition is true.
---
### 29. Definicja funkcji powinna się zaczynać od

**TLDR:** The def keyword
**Detailed Answer:** In Python, function definitions begin with the def keyword, followed by the function name, parentheses, and a colon.
```
def my_function():
    pass
```
---
### 30. Co charakteryzuje zbiór (set)?

- **TLDR:** Unordered collection of unique elements
- **Detailed Answer:** A set in Python is an unordered collection of unique elements. Sets do not allow duplicate values and are defined using curly braces {} or the set() function.
```
my_set = {1, 2, 3}
```
---
### 31. Operator % oznacza

- **TLDR:** Modulo (remainder) operation
- **Detailed Answer:** The % operator in Python is used to find the remainder of the division of two numbers. For example, 10 % 3 results in 1.
---
### 32. Jak sprawdzić czy wartości a i b są równe?

- **TLDR:** Using the == operator
- **Detailed Answer:** To check if two values a and b are equal, you use the equality operator ==.
```
a = 5
b = 5
print(a == b)  # Output: True
```
---
### 33. Rzutowanie listy na krotkę:

- **TLDR:** Using the tuple() function
- **Detailed Answer:** To cast (convert) a list to a tuple, you use the tuple() function.
```
my_list = [1, 2, 3]
my_tuple = tuple(my_list)
print(my_tuple)  # Output: (1, 2, 3)
```
---
### 34. Do pobrania posortowanej tablicy o nazwie my_tab użyjemy operacji

- **TLDR:** sorted()
- **Detailed Answer:** To get a sorted version of the list my_tab, use the sorted() function.
```
my_tab = [3, 1, 2]
sorted_tab = sorted(my_tab)
print(sorted_tab)  # Output: [1, 2, 3]
```
---
### 35. List comprehension pozwala na wygenerowanie listy:

- **TLDR:** Using a concise syntax
- **Detailed Answer:** List comprehension provides a concise way to generate lists in Python. It consists of brackets containing an expression followed by a for clause.
```
squares = [x**2 for x in range(10)]
print(squares)  # Output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```
---
### 36. Metoda __init__() w klasie pełni rolę

- **TLDR:** Constructor method
- **Detailed Answer:** The __init__() method in a class is the constructor method in Python. It initializes a newly created object and allows you to set initial values for the object's attributes.
```
class MyClass:
    def __init__(self, value):
        self.value = value
```
---
### 37. Funkcja random.randint(X,Y) losuje dowolną liczbę

- **TLDR:** Between X and Y (inclusive)
- **Detailed Answer:** The random.randint(X, Y) function returns a random integer between X and Y, inclusive.
```
import random
print(random.randint(1, 10))  # Output: Could be any integer from 1 to 10
```
---
### 38. Jaką wartość ma zmienna x po wywołaniu następującej instrukcji: x = str("2021"+"1")

- **TLDR:** "20211"
- **Detailed Answer:** The expression "2021" + "1" results in the string "20211", and str() simply ensures it's a string (which it already is). Therefore, x will be "20211".
---
### 39. Ile elementów ma lista: x = list(range(1,1))

- **TLDR:** 0 elements
- **Detailed Answer:** The range(1, 1) function generates an empty range, as it starts and ends at 1 without including it. Therefore, list(range(1, 1)) results in an empty list [], which has 0 elements.
---
### 40. Ile razy wykona się poprawna linijka kodu pod linijką o postaci: if true:

- **TLDR:** Infinite loop if the condition was while True:, 1 time for if True:
- **Detailed Answer:** If the code is if True:, it executes once. If it was while True:, it would create an infinite loop.
```
if True:
    print("This prints once.")
```
---
### 41. Jaki błąd zostanie zgłoszony po odwołaniu się do nieistniejącego indeksu listy?

- **TLDR:** IndexError
- **Detailed Answer:** Accessing a non-existent index in a list will raise an IndexError.
```
my_list = [1, 2, 3]
print(my_list[5])  # Raises IndexError: list index out of range
```
---
### 42. Funkcja datetime.datetime.now() zwraca

- **TLDR:** The current date and time
- **Detailed Answer:** The function datetime.datetime.now() returns the current local date and time as a datetime object.
```
from datetime import datetime
print(datetime.now())
```
---
### 43. Jaki jest domyślny tryb otwierania pliku?

- **TLDR:** Read mode ('r')
- **Detailed Answer:** The default mode for opening a file in Python is read mode ('r').
```
with open('file.txt') as file:
    content = file.read()
```
---
### 44. Ile linijek wyświetli się na ekranie po wywołaniu kodu: x = 3*"hahaha"

- **TLDR:** One line
- **Detailed Answer:** The expression 3 * "hahaha" results in the string "hahahahahahahaha" (18 characters long), but it's a single string, so it will print as one line.
### 45. Którego z modułów NIE możemy zaimportować, kiedy korzystamy ze standardowej dystrybucji Pythona?

- **TLDR:** Context-dependent, typically external modules
- **Detailed Answer:** Standard library modules like os, sys, math, datetime can be imported in any standard Python distribution. Modules not included in the standard library, such as numpy, pandas, or requests, need to be installed separately.
---
### 46. Aby sprawdzić długość listy my_list użyjemy operacji

- **TLDR:** len(my_list)
- **Detailed Answer:** To check the length of a list in Python, you use the len() function.
```
my_list = [1, 2, 3]
print(len(my_list))  # Output: 3
```
---
### 47. Metoda my_str.upper() zwraca wartość:

- **TLDR:** The string in uppercase
- **Detailed Answer:** The upper() method returns a copy of the string with all characters converted to uppercase.
```
my_str = "hello"
print(my_str.upper())  # Output: "HELLO"
```
---
### 48. Instrukcja pass w Pythonie

- **TLDR:** Does nothing (a no-op)
- **Detailed Answer:** The pass statement in Python is a null operation; it is used as a placeholder in loops, functions, classes, or conditionals where syntactically some code is required, but you do not want any action to be performed.

```
for i in range(5):
    pass
```
---
### 49. Aby usunąć zmienną, użyjemy instrukcji

- **TLDR:** del
- **Detailed Answer:** To delete a variable in Python, you use the del statement.
```
x = 10
del x
# print(x)  # This will cause an error since x is no longer defined
```
---
### 50. Wyrażenie not(2 == 4) zwraca

- **TLDR:** True
- **Detailed Answer:** The expression 2 == 4 evaluates to False. The not operator inverts this, making not(2 == 4) evaluate to True.
