# Engitrum-club-week2
### Through this week 6 concepts of python programming was covered which are:
* sets.
* condition and branching.
* loops.
* functions.
* exeption handling. 
* object and classes.


## Sets:
* The set is one of Python data types such as tuples, lists, and dictionaries which use to store data in a single variable.What distinguishes sets. are unordered, unchangeable, and unindexed.
* To define sets we use curly brackets {}.
### Exampel:
```
Set1 = {"seconed", "week",True,7}
print(Set1)

```
## Condition and Branching:
* condition is used to determine which instruction will be execute.
* branching is used to allow us to execute multiple instructions based on different conditions.
* we can use,if-else, multiple if, or else if, in order will check when the condition is true do " something" otherwise go to another statement.
### Exampel:
```
a ="red"
b ="blue"

if b==a:
  print("Yes,it's equal")
else:
  print("No,it's diff")

```
## Loops:
* the loop is used to repeat a block of code specific times.
* we can use for , while.
* A for loop is used for iterating over a sequence already specified.
```
names = ["sara", "nora", "amal"]
for i in names:
  print(i) 
  
```
* While loop is used to execute a block of code while the condition is true.
```
i = 0
while i < 6:
  print(i)
  i += 1
  ```
  
 ## Functions:
 * Python provides multiple built-in functions such as len() which return the length of an object, and type() returns the types of an object.
 *  using the "def" keyword you can build your own function, and it's run only when called.
 ```
 def printfun():
  print("Hello ")

printfun()

 ```
 ## Exeption Handling:
 * Is used when we expect errors to avoid crushing the program, the syntax starts with "try" which contains the code want to test, then "except "contains handling for errors, last "finally " contain a block of code executed regardless of the result of the try- and except blocks.
 ```
 #because x is not defined ,,the except block will generate:
try:
  print(y)
except:
  print("An exception occurred")
 ```
 ## Object and Classes:
 * Python is an object-oriented programming language, which means everything is an object with properties and methods.
 * to create a class use the keyword "class".
 ```
 class info:
  def __init__(self, name, age):
    self.name = name
    self.age = age

object1 = info("sara", 20)

print(object1.name)
print(object1.age)
 ```
 
 
