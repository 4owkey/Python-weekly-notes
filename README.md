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
	   
   FUNCTIONS
       
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

     • Using a list comprehension, we can multiply each item in the list.
     • The list comprehension is enclosed in square brackets, and the syntax is similar to that of a for loop.
     • You can use any variable name to represent an item in the list, as long as you use the same consistently throughout.
     • A list comprehension allows you to create a for loop in one line while also returning a copy of the list you're iterating over.
     • It also enables you to filter or apply functions to every item in a list.
     • There's a string function called split, it allows you to split a string based on a given character or string.
     • If no delimiter is specified, the split function will split the string based on spaces.

  DICTIONARIES AND COMPREHENSIONS

     • You can use dictionary comprehensions to create a new dictionary from iterable structure, much like list comprehensions create a new list.
     
     

# Python-week-2

WEEK 2

  DAY 1

   ANATOMY OF A FUNCTION

          • Functions are composed of a name and parameters, which are denoted by the def statement.
          • We have Named Parameters.
          • There is a rule when using keyword arguments in Python i.e. they must come after the positional arguments.
          • The order of the first two arguments is important and cannot be changed.
          • However, after these mandatory arguments, the keyword arguments can be in any order.
          • While optional arguments are useful, there is a functional limitation to how many variables can be anticipated.
          • If we want to allow users to pass in any number of variables, use the asterisk symbol before the argument name to create a pointer to the inputted variables. 
          • This trick works only for positional arguments, not keyword arguments.

      **KWARGS

          • In order to handle keyword arguments, a method called kwargs can be used.
          • Kwags is short for keyword arguments.
          • Print kwargs to see that the keyword arguments are now stored as a dictionary instead of a tuple.
          • This makes sense because keyword arguments have keys and values and can be passed in any order, so a dictionary is a more appropriate data structure for referencing them.

  VARIABLES AND SCOPE

       FUNCTION SCOPE

          • In our earlier section, *args and **kwargs were used to print out the arguments passed into a function.
          • However, there's another method that allows us to access all the variables within a Python function without any asterisks.
          • This method is called the "locals" function.

       LOCALS()

          • Why is it named locals? These are the variable names that are only accessible locally within the function.
          • Remember, variables can be defined by any name within the function definition, and it will be available anywhere within that function.
          • However, trying to reference a variable outside its scope will result in an error. 
          • In Python, there are two types of variables: local variables, which are defined inside the function, and global variables, which are defined outside the function in the main code block.

      GLOBALS()

          • Running the code would result in so many items, some of which are Python's pre-built variables that will come in handy when working with classes and packages.
          • However, Jupyter Notebooks also employ various variables to manage its data.
          • Python has a lot of background processes going on, and the scope of variables available in a specific line of code is what determines which variables can be accessed.

      GLOBAL AND LOCAL SCOPE 

          • The plan is to create two functions: function one with variables A and B, and function two with variables C and B. Both functions will print out their local variables.
          • We will call function one with arguments 1 and 2, and function two with arguments 3 and 4.
          • Each function has its own local variable scope and access to any variables in the global scope.
          • However, they can't access each other's data.
          • We can declare a function within another function, as we did with the inner function in function one.
          • This inner function can only be called within function one. If there is an attempt to call it outside of function one, a syntax error is received.
          • When the local variables in function one are printed, the inner function is defined as a variable

  FUNCTIONS AS VARIABLES

     VARIABLES AS FUNCTIONS

          • Variables and functions both have names and data associated with them.
          • However, for functions, this data includes information about required parameters and the lines of instruction to be executed.
          • In Python, a function is represented as an object.

     VIEWING FUNCTIO WITH DATA _CODE_

          • The "code" attribute of Python function objects can be used to confirm that functions are just variables in Python.
          • Print the variable names and the byte object of all the lines of instruction in a function using this attribute.

     TEXT PROCESSING IN PYTHON

          • There are two text processing operations, and a function that can make the text lowercase, remove punctuation, new lines, and words that are three characters or less.
          • It can also remove long words.

     LAMBDA FUNCTIONS 

          • These are a way to represent a function without giving it a variable name.
          • Just like how an expression like 5 or 2 + 3 can be written without assigning it to a variable, a small function can be defined using the lambda keyword. 
          • Lambda functions can come in handy when you need to pass a function as an argument to another Python function, such as the sorted function that sorts a list of values.
          • Lambda functions are concise and convenient for writing small functions that you need while writing code.

 DAY 2

   ANATOMY OF A CLASS

      INSTANCE ATTRIBUTES

          • The topic of classes can be overwhelming and hard to understand.
	  • We may not be sure what they are or how to determine which class a member belongs to.
   	  • We cannot directly see the value of the legs attribute, even though it is hardcoded in the dog initialization function.
      	  • If we try to access "dog.legs," we will get an error, and we cannot modify the value of legs.

      STATIC ATTRIBUTES

          • Instead of keeping it in the constructor, define it as a static variable outside of the constructor.
	  • This means that each instance of the class will have the same value for legs.
   	  • The legs attribute can be accessed directly on the class itself by calling do.<=gs.
      	  • These variables are called "static" because they don't change with each instance and are commonly used to hold constants or fundamental business logic. 
	  • It is important to note that static variables can still be changed, so to prevent this, programmers conventionally add an underscore before the variable name.
   	  • This indicates that the variable should not be modified directly, and a getter method should be used instead.
          • A getter method retrieves the value of the variable, and in this case, it would be >= t <= gs.
	  • However, this does not actually need to pass in the self attribute for this method, because legs is a static variable in the class.
   	  • Call the method in the traditional way, without passing in self, but it is also possible to call it with self included.
      	  • Classes have their own variable scope rules similar to functions.
	  • If is not set to something else, it references the class variable self.<=gs. 
          • However, the instance variable <=gs can also be modified by assigning a new value to MY(d)Og.<=gs. 

      INSTANCE AND STATIC METHODS

          • The clean text method is a static method because it does not belong to any particular class instance, whereas add text is an instance method that belongs to a particular instance of the class.
	  • Static variables like replace puncs can also be added to control which punctuations get replaced.
   	  • Use either the class name or the class instance to refer to static variables, but cannot be done with instance methods.
          • By adding the @staticmethod decorator to the function definition, it explicitly states in Python that the function is a static method and should not have "self" passed in as an argument.

   INHERITENCE

       CLASS INHERITANCE

          • It is possible for one class to inherit all the methods and attributes of another class.
	  • The original class is referred to as the parent class, while the new class that extends it is known as the child class.
   	  • This inheritance process happens automatically when the child class is created.
          • Child instance class can then be created using all the methods and attributes of the parent class.
	  • You can also add new methods to the child class.

       EXTENDING BUILT-IN CLASSES

          • We can also apply class extensions in Python's built-in classes.
	  • In Python, creating a new list can be done by instantiating it as "list".
          • Although it appears as a function, "list" is actually a class.
	  • Although it appears as a function, "list" is actually a class. 

DAY 3

   HANDLIN ERRORS AND EXCEPTIONS

     	  • When working with Python, notice that sometimes these problems are referred to as errors, while other times are called exceptions.
	  • If official Python documentation is consulted, you will find that exceptions are determined during runtime and can be retried, whereas errors cannot be retried.
          • Here is a controversial opinion: errors and exceptions are basically the same thing.
	  • All Python errors and exceptions ultimately stem from a class called the base exception
          • For instance, the division by zero error is a type of arithmetic error, which is a type of exception, which in turn extends the base exception class.
	  • The base exception class provides useful and powerful properties to exceptions, such as halting code execution and providing information about why and how the execution was halted. 
          • This entire traceback is known as a stack trace.
	  • If you envision these nested calls as a stack of operations, the stack trace provides a trail through the stack that aids in debugging our program.
   	  • We can catch an exception using a try / except statement and obtain an instance of the raised exception.

      TRY/EXCEPT

          • Exceptions when used and handled correctly are almost like a secondary layer of code underlying all the existing and more obvious code.

   MANAGING AND HANDLING EXCEPTIONS
   
	  • There are a few interesting things you can do with this Try / Except pattern.
   	  • For instance, if we do not care about getting the specific instance of the exception, and just want to print something, we do not have to have the as e in order to catch an exception.
      	  • There was some sort of error and then that just prints out.

      FINALLY
      
	  • Another useful tool is the finally statement.
   	  • If you take the Try / Except block and add a finally to it, this will always execute and gets printed out. 
      	  • Finally statements can be useful because they will always execute no matter what happens inside this try block.
	  • You do not even need any except statements! This error is thrown, but still printed out.
          • Even if no exception is raised at all, that still executes.
	  • Often this is used when timing how long a function takes to execute.
   	  • So if we import the time class, import time, this can be used to actually time our function. 
          • Another fun thing to do with this is time.sleep. And time.sleep just pauses execution for a number of seconds. In this case, pause it for half a second.

      CATCHING EXCEPTIONS BY TYPE
   
	  • Notice that you are always catching this exception class.
          • You could add another except statement above this and chain these together just fine. 
	  • The order of these except statements does matter here and Python will try the first one.
          • If you move the general exception up, this is the class from which all of these extend, there was some sort of error. 

      CUSTOM DECORATORS
      
	  • def handleException(func):
	     def wrapper(*args):
	        try:
	            func(*args)
	        except TypeError:
	            print('There was a type error!')
	        except ZeroDivisionError:
	            print('There was a zero division error')
	        except Exception:
	            print('There was some sort of error!')
	    
	     return wrapper
	
	    @handleException
	    def causeError():
	     return 1/0
	
	    causeError()

     	output ->  There was a zero division error

   	  • We are going to pass as an argument, a function, and then define an inner function called wrapper.
      	  • Try to execute this function that was passed in and then paste the exceptions here. Now return this wrapper function. 
	  • Make a decorator handleException and put it on a causeError function.
          • This is just going to return one over zero. 
	  • If we call causeError, this handle exception was used to accept those various exceptions that this could throw.

      RAISING EXCEPTIONS

          • Let's talk about raising exceptions.
	  • Use the handle exception decorator.
   	  • Make a  function called raiseError raise Exception.
      	  • This raise statement raises or throws this new exception that was created when it is reached. 
	 
	  •     @handleException
		def raiseError(n):
		    if n == 0:
		        raise Exception()
		    print(n)
		
		raiseError(1)
  
              OUTPUT -> 1
	      
   	  • Notice that an else statement is not used.
      	  • This is not needed because once the exception is raised, this execution will halt, and throw this exception and then the print n will never be reached.
	  • Notice in the handleException function, this is the function that gets passed in, this raiseErrors being passed in, but when we call it, there are no arguments even though our function has an argument.

   WORKING WITH CUSTOM EXCEPTIONS
   
          • Class CustomException extends Exception:pass.
	  • The pass statement is used because we literally do not need to define anything for our new CustomException class
          • It inherits the constructor of the Exception class that it is extending.
	  • Custom exceptions are usually lightweight classes with very little in the way of special attributes and methods and things, but might have some attributes that are useful for organizing and presenting information to the user about the error.

Day 4

   FUNDAMENTALS OF THREADS AND PROCESSES
      
          • Computers have both memory and file storage.
	  • It is like short-term and long-term memory.
   	  • When we save a file and load to file from the disc, that is in storage i.e. long-term memory.
          • When we declare a variable in our program, that is short-term memory in the processor.
	  • They both have access to the same long-term storage on the physical machine, but if this program writes something to memory, the second program cannot access it. 
          • The operating system is responsible for allocating memory to each process running on the computer.
	  • It puts walls between the processes so they cannot access each other's memory.
          • Memory is not one giant vague blob like implied. It is segmented. Access is controlled by the operating system. 
   	  • We still get to run them in parallel, at the same time, but instead of separate processes, they are run with separate threads. 
	  • A process can have multiple threads and execute code at the same time in parallel.

   MULTITHREADING
   
   	  • On VS code.

   MULTIPROCESSING
   
          • How do we write a program to start, stop, and manage these for us? Well, conveniently, there is a module that is very similar to the threading module we used previously.
	  • That module is called multiprocessing. 

Day 5

   OPENING, READING AND WRITING

      READING FILES
   
          • Watching output being printed to the screen is all well and great, but often as programmers, we are asked to produce something real, something tangible, usually for those management types that want to see a physical file they can attach to email or open in Excel or whatever it is they do with files.
	  • Sometimes they give you files and they want your program to read them.
          • We are working a little more directly with the operating system and so there are some things that you need to manage.
	  • And one of those things is whether we are simply reading the contents of the file or whether we intend to make changes to it. 
   	  • This is because it causes problems if two applications are making changes to the same file at the same time.
          • The operating system needs to know who's doing what.
	  • You can use the open function and pass in the name of a file.

     WRITING FILES
   
   	  • We're going to open this file in the read mode and if we print f at this point, we get a file object.
      	  • And there are a couple of ways to get the actual text inside the file. And the first is readline, so f.readline. This reads the lines of the file one at a time. 
	  • When you run it again, you get a different line each time. So this file object contains some sort of bookmark of which lines of the file are already read. 
	  • You could put f.readline inside of a loop and get all the lines of the file, but there is an easier way to get all the lines of the file, and that is readlines, plural.
   	  • This gets all of the lines of the file that have not been read already and puts them into a list of strings.
      	  • We can print out the contents of this file fairly nicely if we do something like this, for line in f.readlines, print line. 
	  • Notice that these lines are all double-spaced and that is because each line of the file has a new line character on it on the end there, and this print statement also includes its own new line.
          • We can fix this by stripping out any leading or trailing white space, including new lines, and we do that with the strip function on each line. Beautiful, and that is better than ugly. 

     APPENDING FILES
     
	  • Let's look at writing files. We are going to do something similar to this but instead of an R, use a W for write. 
   	  • We are also going to call this output.txt, which does not exist yet, but when we run this, it will create the file for us which is a pretty nice feature. 

 CSV

     READING
     
      	  • Notice that this did not quite parse correctly, and that is because this is not the traditional comma-delimited, comma-separated value that you are used to seeing.
	  • The CSV file actually contains tab-separated values. So all of these are tabs.
          • We can fix this output by taking the spac slash T and passing it in as a delimiter argument, backslash T right there.
	  • But if you have something other than a comma, you need to put in that delimiter specifically. 
          • You can also see that the first row that gets printed out here is the header. And if you want to skip the header, the CSV reader also has a neat function you can use called next
	  • If we say list CSV reader, we do not have to call next, we can just use the list slicing syntax like that and that will also skip over the header.
     
     FILTERING DATA
     
   	  • ON VS CODE.

     JSON

     	  • Something to keep in mind, JSON is not Python.
	  • This JSON-formatted string looks a lot like a Python dictionary, but it's not. It's a string.
   	  • This is a string that just happens to be in the JSON format and in order to turn it into a dictionary, we need to import the JSON module at the top of our notebook, import json, and then use a method called json.loads and pass in the string, jsonString. 
          • Notice that this is called loads plural and not load singular.
	  • You can copy this Python dictionary and add a trailing comma, and that is just fine, but if you add a trailing comma to this JSON string, we get a JSON decode error.

      DUMPING JSON
      
          • Notice that this is dumps plural.
	  • You usually would not add any exception handling in this case because if you have a valid Python dictionary, there is not a lot that could go wrong when you are formatting it as a JSON string. 
   	  • However, there is one exception to this rule where an exception could be thrown.

      CUSTOM JSON DECODERS
      
      	  • ON VS CODE
	  
	  
     









      
          



      
     
     










    
