## Keywords in Python
---
#### _All the keywords except True, False and None are in lowercase and they must be written as they are. The list of all the keywords is given below._
#
| 1 | 2 | 3 | 4 | 5 |
| ------ | ------ | ------ | ------ | ------|
|False|await|else|import|pass
|None|break|except|in|raise
True|class|finally|is|return
and|continue|for|lambda|try
as|def|from|nonlocal|while
assert|del|global|not|with
async|elif|if|or|yield

**Gettings Keywords Programmatically**
```
import keyword
print(keyword.kwlist)
```
**Output from python**
```
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
```

**Description of keywords**

| Keywords | Description
| -----| -----|
and|A logical operator
as|To create an alias
assert|For debugging
break|To break out of a loop
class|To define a class
continue|To continue to the next iteration of a loop
def|To define a function
del|To delete an object
elif|Used in conditional statements, same as else if
else|Used in conditional statements
except|Used with exceptions, what to do when an exception occurs
False|Boolean value, result of comparison operations
finally|Used with exceptions, a block of code that will be executed no matter if there is an exception or not
for|To create a for loop
from|To import specific parts of a module
global|To declare a global variable
if|To make a conditional statement
import|To import a module
in|To check if a value is present in a list, tuple, etc.
is|To test if two variables are equal
lambda|To create an anonymous function
None|Represents a null value
nonlocal|To declare a non-local variable
not|A logical operator
or|A logical operator
pass|A null statement, a statement that will do nothing
raise|To raise an exception
return|To exit a function and return a value
True|Boolean value, result of comparison operations
try|To make a try...except statement
while|To create a while loop
with|Used to simplify exception handling
yield|To end a function, returns a generator