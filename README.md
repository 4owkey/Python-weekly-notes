WEEK 1

 Day 1
	 
   PYTHON INTRODUCTION
		
     • Python is a highly popular dynamic programming language uswd by numerous large organisations, such as Google, Yahoo and IBM.
	   • It is compatible with all major operating systems and often comes pre-installed on Macs, as well as most Linux and Unix-based systems.

   WHY IT'S POPULAR

	   • Due to it's intuitive syntax.
	   • It's easy to use. 
	   • Similar to other programming languages.
	   • It's an excellent gateway language it's easy to transfer your python skiplls to other languages you might program with in the future.
	   • Having prior programming knowledge is also beneficial. 

   VARIABLES AND DATA TYPES

	   • The basic unit of a program is called a variable, which is assigned a value.
	   • An equal sign is an assignment operator.
	   • If a variable name begins with a number, it cannot be used, but a variable name can include upper and lower case letters, as well as underscores.
	   • Variable names traditionally begin with lowercase letters in python.

   TYPES OF VARIABLES

	   • Integers -> Whole numbers. 
	   • Floats   -> Decimal numbers.
	   • Strings  -> Collections of characters.
	   • Booleans -> True or False value. 
	   • Complex numbers  -> Complex maths calculations. 
     • When working with strings, the plus sign is used to concatenate them. 

   DATA STRUCTURES
    	   
	   • In Python data structres allow for the storage of a list of values in a single variable.
     • The first data structure we learn about is a list, which can contain any data type, including a list within a list.
	   • A set is similar to a list, except it only contains unique elements and is declared using curly braces.
     • The order of elements in a set is not important, unlike in a list.
	   • Tuples are similar to lists, except they cannot be modified once declared. 
     • They are useful when you need to store large amounts of data more efficiently in memory, like XY coordinate pairs.
	   • A dictionary is a collection of key-value pairs, similar to a word and its definition in a book. 
     • Dictionaries are declared using curly braces and accessed using keys.

   OPERATORS

     • Operators are instructions that perfom operations on variables and valves in Python. 
	   • They are used manipulate and perfom actions on data.
     • Arithmetic operator -> Which is used for mathemacal calculations.
	   • Example of operations, equal sign, addition, multiplication and exponent operator which raises a number to a specified power.
     • Division can be performed using the foward slash operator,  and it returns a floating-point value, even if the result is a whole number.
	   • The modules operator is specific to pragramming and provides the remainder after division. 
     • String can also be manipulated using operators. The addition operator can concatenate or combine two strings together, while the multiplication operator can repeat a          string a certain number of times.
     • Comparison operators evaluate two variables or values and produce a boolean result, either true or false.
	   • Logical operators, such as "and", "or", and "not", operate on  boolean values. 
     • The "and" operator returns true only if both operands are true, while the "or" operator returns true if at least one operand is true.
	   • The "not" operator negates the boolean value it operates on.
     • Membership operators, "in" and "not in", are used to check whether a value is present in a sequence or not. 

   CONTROL FLOW
       
     • The if statement is one of the three main types of control flow in programming,  and it allows you to execute a block of code only if a certain condition is met.
	   • Indentation is very important and determines the structure if your program.
     • You can a for loop to iterate over a list or any iterable object.
	   • The item in the for loop is just a variable that represents the current item in the list, and you can name it anything you want.
     • A while loop is similar to a for loop, but it keeps looping until a certain condition is false.
	   • It's important to make sure that the condition in the while loop will eventually become false, otherwise, the loop will continue indefinitely.

Day 2 
	   
   Functions
       
     • A function is like a machine that takes inputs and produces outputs.
	   • Functions can be defined using the "def" keyword followed by the function name and arguments in parentheses.
     • The function body is indented and contains the code that performs the desired operation on the inputs, and the "return" keyword is used to specify the output.
	   • Functions can take one or more arguments, and they may or may not return a value.
     • The print function is an example of a function that does not return anything, but rather prints output to the console.
	   • The special python keyword "None" represents the absence of value, and it is the defualt return value for functions that do not explicitly return anything.
       
   CLASSES AND OBJECTS

     • A class in python, can help label and organise related collections of functions and attributes.
	   • We can create a class called Dog, as it has multiple functions and attributes, such as legs, a name and bark.
     • When we define a class, we use an uppercase letter for the class name, and we start defining all the functions and attributes inside the class definition.
	   • We usually begin by creating a special functon called the initialization function, or "init" function, which gets called every time an instance of the class is created.
     • The init function takes in a variable called "self", which refers to the specific instance of the dog class.
	   • We can access any of the attributes or functions in the class using the "self" variable.

   INTS AND FLOATS

	   • Python automatically return a float to accomodate non-whole numbers. 
     • To convert a float number to an int number we can use an int class and its not a function.
	   • Int is a built-in class in Python, along with other types like strings, floats and lists.
     • Python doesn't round when casting floats to ints, it merely removes the decimal part.
	   • To round a float to the nearest int we can use the round function.
     • Pitfall of floats is that they are approximations, which can result in rounding errors.
	   • Using the round function can mitigate this issue.

   ALTERNATIVE NUMBER TYPES

	   • If you pass a number as a string, the int class will convert it to an integer.
     • If you pass a second argument as a number, it will convert the first argument from that base to base 10.
	   • The first argument must always be a string, even if you want to convert it from a different base.
     • Floats have floating point errors that can be problematic in certain situations, such as when dealing with money.
	   • To use the decimal module, you need to import the decimal class and the getcontext function at the top of your code.
     • The getcontext function returns a context object that holds global settings for using the decimal class.
	   • You can change these settings by modifying the attributes of the context object, such as the precision.
     • With decimal class,  you can instantiate a decimal object with a number value.

   BOOLEANS

	   • Python easily casts integers to booleans, -1 is true and 0 is false.
     • Anything axcept 0 is true.
	   • Empty string is false, but it should not have a space in there.
     • Booleans are usually used in if statements or loops.
     • An empty list is false, but anything inside is true.
     • When python returns a non-value from a function, it is cast to false.

  STRINGS

     • One of the useful tool in python is Slicing.
     • Slicing refers to taking a portion of a string and returning it.
     • Python, has a few ways of creating a string, including string concatenation and f-strings.
     • F-strings allow us to insert variables or expressions inside curly braces in a string.
     • We can also do rounding and number formatting with f-strings.
     • Python has a handy feature for creating multiline strings by using triple quotes in the string, we can escape them with backslash.

Day 3

  BYTES

     • It's data that is passed around but rarely modified directly. 
     • When computers store information, it's done as ones and zeros.
     • When python loads that data, it knows what type it is - string, int, class, etc.
     • The bytes object is commonly used for streaming files or transmitting texts without knowing the encoding.
     • Each byte has eight bits. 
     • If you see a b in front of something printed out, it's a bytes object.
     • To create a bytes object with actual data in it, like an emoji, you need to tell python the type, like utf-8.
     • You can also use the decode function to turn bytes back into a string.
     • Bytes objects are immutable, like tuples but you can use a byte array if you need to modify the data.
     • You can treat a byte array like a string and modify specific byte values using slice notation.
     • You can use the int library to convert hexadecimal values, like a shrugging emoji, back to bytes. 
     • That's how to find, detecct, use and modify bytes in Python.

  LISTS

     • Slicing can be used to extract a range of values from a list or string, and you can also add a third value to control the step size.
     • Range function can be used to generate longer lists, which can be also sliced.
     • If we want to insert an item at a specific position in the list, we can use the insert() method.
     • 2 ways to remove items from a list.
       1. Remove() method - Which removes an item based on its value, not it's index.
       2. Pop() method - Removes and returns the item at the end of the list. 
     • We can also use a loop(for,while) with pop() to remove all items from the list.
     • When we assign a list to a variable, the variable stores a refernce to the list, not a copy of the list.
     • This means that if we modify the list through one variable, the cahnges will be reflected in other variables that reference the same list.
     • If we want to make a copy of a list so that changes to one list don't affect the other, we can use the copy() method, e.g b = a.copy().

  TUPLES AND SETS

     • You can also define a set by passing any iterable object in the constructor of the set class, like this: mySet = set(('a','b','c'))
     • One common use of sets in programming is to remove duplicates from a list, since sets only contain unique values. 
     • Sets are not ordered lists but rather collections of elements so their order is randomized.
     • You can also check if an element is in a set using the membership operator (in) and find the length of a set using the length function.
     • Sets have pop() function that removes and returns an arbitrary element from the set.
     • Tuples are similar to lists, but they're declared with parentheses instead of square brackets.
     • You can retrieve elements from a tuple using indexing, but if you try to modify them, you'll get an error.
     • Tuples are more efficient than lists becuase they take up less memory. 
     • You don't even need to use parentheses, although it's recommended for readability.
     • You can also unpack the values in a tuple into  individual variables using the syntax A,B,C = myTuple.

Day 4

  DICTIONARIES

     • Combining lists and dictionaries can solve nearly 95% of your data structure needs.
     • To access a specific key-value pair in the dictionary, you can simply type the name of the dictionary followed by the key in square brackets.
     • To add a new key-value pair, you can use a similar syntax with the assignment operator.
     • If you want to update an existing key-value pair, simply access it and reassign it a new value.
     • You can also access the keys and values of a dictionary using the .key() and .value() methods, respectively.
     • If you're unsure if the key exists or not, you can use an if-else statement to handle both cases.
     • Defualt dict, which you can import from the collections package.
     • To create a defualt dict, you need to specify the type of object it should return by defualt.
     • Don't make the common mistake of passing in an instance of the object you want returned.
     • You need to give it a callable function that creates the object.
     • Once you have your defualt dict, you can add items to it like you would a regular dictionary.

Day 5

  LIST COMPREHENSIONS

      
     
     










    
