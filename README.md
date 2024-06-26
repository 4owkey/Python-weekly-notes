# Python-week-1

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

# Python-week-3

  Day 1
	
	    • Starting with user stories, which depict small scenarios from a user's perspective, these stories should emphasize the user's goal and motivation rather than the application itself.
	    • User stories are brief, simple, and informal, perfect for jotting down on index cards. They typically follow the format "As a [user/role], I want [goal] so that [reason/benefit]".
	    • They typically follow the format "As a [user/role], I want [goal] so that [reason/benefit]".
	    • It's essential to avoid overloading the application with every possible feature right from the start.
	    • The initial scope should be kept manageable, while ideas for additional features can be maintained separately in a backlog.

 	USE CASES
  
	    • Use cases typically include a title, an actor (a user or system), and a scenario that describes how a goal is achieved.
	    • The scenario can be written as a paragraph or a list of steps in simple language.
	    • While user stories and use cases may seem similar, they capture different information.
	    • User stories focus on the who, what, and why of a task or goal, while use cases cover the who, what, and how of achieving that goal.
	    • They complement each other rather than compete.
     	    • Depending on the complexity of your project, you may choose to use user stories alone or combine them with use cases.
	    • Besides user stories and use cases, it's helpful to write traditional requirements to formally capture the capabilities and limitations of an application.
            • Functional requirements describe what the application should or should not do and are written as sentences starting with "the application must" or "the application shall."
	    • In addition to functional requirements, non-functional requirements describe how the application should accomplish its tasks.
            • They focus on qualities like maintainability, reliability, and usability.
	    • For example, the application should have a configurable GUI for the admin to interact with, be extensible for adding more content types, and be resilient to content errors.

        ARCHITECTURE
     
     	    • Now that the requirements are captured, it's time to organize and structure the code for the application.
	    • With Python being an object-oriented programming language, considering objects and classes is essential.

     STUB CODE
     
            • It's time to start coding, and to provide a structure for the design, stub code has been created for the entire program using three Python modules: dd_content.py, dd_email.py, and dd_gui.py.
	    • The dd_email.py module contains the skeleton for the daily digest email class, with placeholder methods using the pass statement.
     	    • This allows the script to be executed without errors, even though it doesn't have any useful functionality yet.
	    • The if name equals the main section at the bottom of the script can be used to add test code corresponding to the email class.
            • Moving on to the dd_content module, a similar if name equals main section is included for test code.
	    • Unlike the daily digest email module, the dd_content module does not define a daily digest content class.
     	    • Instead, after consideration, it was decided that independent functions to retrieve random quotes, weather forecasts, Twitter trends, and Wikipedia articles would be more suitable.
	    • These functions are included in the dd_content module, allowing easy expansion with additional content sources in the future.
            • The dd_gui module handles the graphical user interface for the email digest administrator and utilizes the TKinter module.
	    • To implement the "get_random_quote" function, the source of random quotes needs to be determined.
     	    • While web scraping libraries like Beautiful Soup or Scrapy could be used, after exploring options, a decision is made to curate a personal list of inspirational quotes.
	    • Storing the quotes and their authors can be done using different file formats like CSV, JSON, or XML.
            • In this case, the CSV format is chosen for simplicity, with each line containing the author and quote separated by a vertical pipe symbol.
	    • The file loading code is wrapped in a try-except block to handle potential exceptions.
     	    • The CSV file is opened, and a list of dictionaries is created using list comprehension, where each dictionary represents an author and their quote.

     WEATHER FORECASTING WITH OPENWEATHERMAP
     
	    • Since the weather forecast data needs to be current, we can't store it in a local CSV file like we did for the quotes.
            • Instead, we will need to fetch the weather information from the internet.
	    • One option is to use a Python web-scraping library to extract forecast information from a website like weather.com.
     	    • Another option is to search the Python Package Index for a Python library that can retrieve weather data from an online source.
	    • Alternatively, we can find an online source of weather information that provides an API we can directly call from our program.
            • In the beginning of the dd_content script, you should have imported three new modules: the request module from the urllib package to open the API's URL, the JSON module to parse the response, and the datetime module to format and store the timestamp for each forecast period.
	    • Moving down to line 25, there is a function called get_weather_forecast that includes an optional parameter named coords, which is a dictionary holding the desired latitude and longitude.

     WRITING AND FORMTING EMAIL MESSAGES
     
     	    • Before we can send an email, we need something to send, so the next method we'll tackle is the format message.
	    • Initially, when planning the class requirements, there was a method called format message that was meant to format various content into the email's message body.
            • There are multiple ways to format an email, including plaintext or HTML.
	    • In the init constructor method, an instance variable is initialized as a dictionary to store the four types of content, each with a Boolean flag indicating if it should be included. 

     SENDING AN EMAIL
     
            • Luckily, Python has a convenient library called 'email' in its standard package, which helps manage email messages. 
	    • The core of this module revolves around a class known as "Email Message."
     	    • It is the main tool used to put together different components of the daily digest email, like the subject line, recipient list, and, of course, the message content.
	    • In other Python modules like SMTP-Lib, you can find the same functionality.
     	    • This module lets you create a client session to send emails through an SMTP server.
	    • Let's see how the send email function works. Firstly, we imported two new modules: 
            • SMTP-Lib, which helps us connect to the outlook server, and the email message class from the email.message module.
	    • To store the email address and account password for sending the digest, we created a dictionary.
     	    • Moving on, the send email function begins by creating a new email message object. 

    TASK SCHEDULING
    
	    • ON VS CODE

     GUI DESIGN PLANNING
     
            • Normally, leave GUI development until the end of a project.
	    • This way, you can ensure that the necessary foundation of the application is built first before creating a visually impressive GUI that would not be of much use without the underlying functionality.
     	    • Either sketch ideas on a piece of paper or play around with shapes on PowerPoint slides.
 
     EXPLORING PYTHON TKINTER GUI
	    • The GUI module, called "dd GUI," consists of 250 lines.
            • Focus on key design decisions, and find the complete code in the exercise files for more detailed exploration. 
	    • CHECK MORE INFO ON VSCODE


# Data Analysis

WEEK 1

 DAY 1

  WHAT IS DATA ANALYSIS?

    - Analytics is at the heart of modern business.
    - Virtually every organization collects large quantities of data about its customers, products, employees, and service offerings. Managers naturally seek to analyze that data and harness the information it contains to improve the efficiency, effectiveness, and profitability of their work.
    - The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization.
    - This involves several key responsibilities and skills.
    
    1. Data Collection and Preparation:
       - Sourcing data from various channels, including databases, spreadsheets, and external sources,
       - Cleaning and organizing the data to ensure it is accurate, consistent, and ready for analysis.
         
    2. Data Analysis:
       - Employing statistical methods, machine learning techniques, or other analytic tools to interpret data,
       - Identifying trends, patterns, and correlations that might not be immediately obvious.

    3. Data Visualization and Storytelling:
       - Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,
       - Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,

    4. Decision Support:
       - Making recommendations based on data-driven insights to help guide business decisions,
       - Providing context around the data, including potential implications and future trends.

    5. Collaboration and Communication:
       - Working closely with other departments, such as marketing, finance, and operations, to understand their data needs and provide insights,
       - Effectively communicating complex data findings in a clear and concise manner to non-technical stakeholders,
      
    6. Continuous Learning and Adaptation:
       - Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.
       - Adapting to new types of data and analytical methods as the organization's needs evolve.

    - By fulfilling these roles, a data analyst helps an organization make informed decisions that can improve operational efficiencies, drive business strategies, and create a competitive advantage.
    - The goal is to contribute to the organization's success by turning data into a valuable asset that informs and drives decision-making.
    - Data analysts are the professionals who possess the skills and knowledge required to perform this vital work.
    - They understand how the organization can acquire, clean, and transform data to meet the organization's needs.
    - They are able to take that collected information and analyze it using the techniques of statistics and machine learning.
    - They may then create powerful visualizations that display this data to business leaders, managers, and other stakeholders.

  THE ANALYTICS PROCESS

    - The process they move through as they acquire new data, clean and manipulate that data, analyze it, create visualizations, and then report and communicate their results to business leaders.

   THE ANALYTICS PROCESS IS ITERATIVE

    - While we describe the steps of the analytics process as a series of sequential actions, it is more accurate to think of them as a set of interrelated actions that may be revisited frequently while working with a dataset.
    - For example, an analyst reviewing a visualization may notice unusual data points that do not seem to belong in the dataset, causing them to return to the data cleaning stage and rerun their analysis with the newly cleaned dataset.
    - Similarly, an analyst running an analysis might discover that their analysis would be enriched by adding another source of data, causing them to return to the data acquisition stage.

   ANALYTICS TECHNIQUES

    - Analysts use a variety of techniques to draw conclusions from the data at their disposal.
    
    - Major categories of analytics techniques.
      * Descriptive Analytics
      * Predictive Analytics
      * Prescriptive Analytics

   MACHINE LEARNING, ARTIFICIAL INTELLIGENCE AND DEEP LEARNING

    - The work of analytics is intellectually and computationally demanding. Fortunately, you do not always have to do this work yourself; you can rely on automated techniques to help you unlock the hidden value in your data.
    - Machine learning uses algorithms to discover knowledge in your datasets that you can then apply to help you make informed decisions about the future.

   SOME COMMON CASES WHERE MACHINE LEARNING COMMONLY ADDS VALUE

      * Segmenting customers and determining the marketing messages that will appeal to different customer groups.
      * Discovering anomalies in system and application logs that may be indicative of a cybersecurity incident.
      * Forecasting product sales based on market and environmental conditions.
      * Recommending the next movie that a customer might wish to watch based on their past activity and the preferences of similar customers.
      * Setting prices for hotel rooms far in advance based on forecasted demand,

      - Machine learning can bring value to almost every field where discovering previously unknown knowledge is useful—and we challenge you to think of a field where knowledge doesn't offer an advantage!
      
      - Artificial intelligence (AI) includes any type of technique where you are attempting to get a computer system to imitate human behavior.
      
      - Machine learning (ML) is a subset of AI techniques.
      - ML techniques attempt to apply statistics to data problems in an effort to discover new knowledge.
      - Or, in other terms, ML techniques are AI techniques designed to learn.
      
      - Deep learning is a further subdivision of machine learning that uses quite complex techniques, known as neural networks, to discover knowledge in a particular way.
      
      - It is a highly specialized subfield of machine learning that is most commonly used for image, video, and sound analysis.
  
   DATA GOVERNANCE

     - We discussed the three major forces that have come together to create the Golden Age of Analytics: data, storage, and computing.
     - Without strong governance, analytics programs cannot function effectively.
     - Data governance programs ensure that the organization has high-quality data and is able to effectively control that data.

   ANALYTICS TOOLS

     - Software helps analysts work through each one of the phases of the analytics process.
     - These tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data. 


   EXPLORING DATA TYPES

     - To understand data types, it is best first to understand data elements.
     - A data element is an attribute about a person, place, or thing containing data within a range of values.
     - Data elements also describe characteristics of activities, including orders, transactions, and events.
     - A data type limits the values a data element can have.

   TABULAR DATA

     - Tabular data is data organized into a table, made up of columns and rows.
     - A table represents information about a single topic.
     - Each column represents a uniquely named field within a table, also called a variable, about a single characteristic.
     - The contents of each column contain values for the data element as defined by the column header.
     - Spreadsheets, including Microsoft Excel, Google Sheets, and Apple Numbers, are practical tools for representing tabular data.
     - A relational database management system (RDMS), commonly called a database, extends the tabular model.
     - Instead of having all data in a single table, a database organizes related data across multiple tables.
     - The connection between tables is known as a relationship.
     - Oracle, Microsoft SQL Server, MySQL, and PostgreSQL are examples of database software.

  STRUCTURED DATA TYPES

     - Structured data is tabular in nature and organized into rows and columns.
     - In a spreadsheet, cells are where columns and rows intersect.
  
  CHARACTER

     - The character data type limits data entry to only valid characters.
     - Characters can include the alphabet that you might see on your keyboard, as well as numbers. 
     - Alphanumeric is the most widely used data type for storing character-based data.
     - As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters.

  CATEGORIES OF DATA

     - Semi-structured data represents the space between structured spreadsheets and unstructured videos.

   QUANTITATIVE VS QUALITATIVE DATA

     - Regardless of structure, data is either quantitative or qualitative.
     - Quantitative data consists of numeric values. 
     - Data elements whose values come from counting or measuring are quantitative.
     - Qualitative data consists of frequent text values.

   DESCRETE VS CONTINUOUS DATA

     - Numeric data comes in two different forms: discrete and continuous.
     - A helpful way to think about discrete data is that it represents measurements that can't be subdivided.
     - Another way to think about it is that discrete data is useful when you have things you want to count. 
     - When you measure things like height and weight, you are collecting continuous data.
     - While whole numbers represent discrete data, continuous data typically need a decimal point.

   CATEGORICAL DATA

     - In addition to quantitative, numeric data, there is categorical data.
     - Text data with a known, finite number of categories is categorical.
     - When considering an individual data element, it is possible to determine whether or not it is categorical.
     - Animal Type is a good example of categorical data. 

   DIMENSIONAL DATA

     - Dimensional modeling is an approach to arranging data to facilitate analysis. 
     - Dimensional modeling organizes data into fact tables and dimension tables. Fact tables store measurement data that is of interest to a business. 
     - Dimensions are tables that contain data about the fact.

   COMMON DATA STRUCTURES

      - In order to facilitate analysis, data needs to be stored in a consistent, organized manner.
      - When considering structured data, several concepts and standards inform how to organize data.
      - Unstructured data has a wider variety of storage approaches.
      - Improved integration and interoperability between tools make it easier for analysts to be productive.

Day 2
   STRUCTURED DATA

      - Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows.
      - Data is consistent when all entries in a column contain the same type of value.
      - Structured data also makes summarization easy, since you can compute the average height for each animal in Table 2.1.
      - It is common to perform summarization across groups.
      - It is a best practice to specify a key that uniquely identifies all values for a given row.

   UNSTRUCTURED DATA

      - Unstructured data is qualitative, describing the characteristics of an event or an object.
      - Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data.
      - This data is unstructured and can identify machine-to-machine interaction. 
      - Machine data is a common source of unstructured data.
      - Machine data has various sources, including Internet of Things devices, smartphones, tablets, personal computers, and servers.
      - Object storage facilitates the storage of unstructured data.
      - The key-value concept underpins the design of object storage.
      - The key is a unique identifier, and the value is the unstructured data itself. 

   SEMI-STRUCTURED DATA

      - Semi-structured data is data that has structure and that is not tabular. 
      - Email is a well-known example of semi-structured data.
      - Every email message has structural components, including recipient, sender, subject, date, and time.
      - he need to make semi-structured data easier to work with has led to the emergence of semi-structured formatting options. 
      - These formatting options use separators or tags to provide some context around a data element.

   COMMON FILE FORMATS

      - These formatting options use separators or tags to provide some context around a data element.

      TEXT FILES

      - One of the reasons text files are so widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software.
      - Text files are also commonly referred to as flat files.
      - A unique character known as a delimiter facilitates transmitting structured data via a text file.
      - The delimiter is the character that separates individual fields.
      - When a file is comma-delimited, it is known as a comma-separated values (CSV) file.
      - Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.

      FIXED-WIDTH FILES

      - Fixed-width files are more laborious to create since they require a few extra steps. 

      JAVASCRIPT OBJECT NOTATION

      - JavaScript Object Notation (JSON) is an open standard file format, designed to add structure to a text file without incurring significant overhead.
      - One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages.
      - Languages such as Python, R, and Go have libraries containing functions that facilitate reading and writing JSON files.

      XML

      - Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file.
      - While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags.
      - While these tags help readability, they add a significant amount of overhead.
      - In 1999, XML was the data format of choice and facilitated Asynchronous JavaScript and XML (Ajax) web development techniques.
      - With JSON as a lighter-weight alternative to XML, it is becoming increasingly popular when interacting asynchronously between a web browser and a remote server.

week 2

  Day 1

    DATABASE USE CASES

      - Databases tend to support two major categories of data processing: Online Transactional Processing (OLTP) and Online Analytical Processing (OLAP).

      OLTP

      - OLTP systems handle the transactions we encounter every day.
      - OLTP systems balance the ability to write and read data efficiently.

      NORMALIZATION

      - Normalization is a process for structuring a database in a way that minimizes duplication of data.
      - One of the principles is that a given piece of data is stored once and only once.
      - As a result, a normalized database is ideal for processing transactions.
      - First normal form (1NF) is when every row in a table is unique and every column contains a unique value. 
      - Second normal form (2NF) starts where 1NF leaves off.
      - In addition to each row being unique, 2NF applies an additional rule stating that all nonprimary key values must depend on the entire primary key.
      - Third normal form (3NF) builds upon 2NF by adding a rule stating all columns must depend on only the primary key.

      OLAP

      - OLAP systems focus on the ability of organizations to analyze data. 
      - While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different.
      - OLTP databases need to balance transactional read and write performance, resulting in a highly normalized design.
      - Typically, OLTP databases are in 3NF.
      - On the other hand, databases that power OLAP systems have a denormalized design.
      - Instead of having data distributed across multiple tables, denormalization results in wider tables than those found in an OLTP database.

      SCHEMA CONCEPTS

      - The design of a database schema depends on the purpose it serves.
      - A data warehouse is a database that aggregates data from many transactional systems for analytical purposes.
      - Transactional data may come from systems that power the human resources, sales, marketing, and product divisions.
      - A data warehouse facilitates analytics across the entire company.
      - A data mart is a subset of a data warehouse. 
      - Data warehouses serve the entire organization, whereas data marts focus on the needs of a particular department within the organization.
      - A data lake stores raw data in its native format instead of conforming to a relational database structure.
      - Using a data lake is more complex than a data warehouse or data mart, as it requires additional knowledge about the raw data to make it analytically useful.
      - Relational databases enforce a structure that encapsulates business rules and business logic, both of which are missing in a data lake.
      - It is crucial to realize that the structure of a database schema impacts analytical efficiency, particularly as the volume of data grows.
      - In addition to a schema's design, it is vital to consider the life cycle.



DAY 2

  HANDLING DIMENSIONALITY

      - There are multiple ways to design dimensions. 
      - Another approach is to use an indicator flag for the current price. This approach requires another column
      - The indicator flag method keeps all pricing data in a single place.

  DATA ACQUISITION CONCEPTS

      - To perform analytics, you need data.
      - Data can come from internal systems you operate, or you can obtain it from third-party sources.

   INTERGRATION

      - Data from transactional systems flow into data warehouses and data marts for analysis.
      - OLTP and OLAP databases have different internal structures.
      - You need to retrieve, reshape, and insert data to move data between operational and analytical environments.
      - One approach is known as extract, transform, and load (ETL). 
      - Extract, load, and transform (ELT) is a variant of ETL.
      - With ELT, data is extracted from a source database and loaded directly into the data warehouse.
      - Once the extract and load phases are complete, the transformation phase gets underway.
      - One key difference between ETL and ELT is the technical component performing the transformation.
      - With ETL, the data transformation takes place external to a relational database, using a programming language like Python.
      - ELT has an advantage in the speed with which data moves from the operational to the analytical database.

  ETL VENDORS

      - Whether you choose ETL or ELT for loading your data warehouse, you don't have to write transformations by hand.
      - Many products support both ETL and ELT.
      - Before you pick one, carefully evaluate the available free and paid options to determine the one that best fits your needs and system architecture goals.
      - An initial load occurs the first time data is put into a data warehouse. 
      - After that initial load, each additional load is a delta load, also known as an incremental load.
      - A delta load only moves changes between systems.
      - The frequency with which delta loads happen depends on business requirements.
      - Depending on how fresh the data needs to be, delta loads can happen at any interval.
      - When moving data between systems, you have to balance the speed and complexity of the overall operation.

   DATA COLLECTION METHODS

      - Augmenting data from your transactional systems with external data is an excellent way to improve the analytical capabilities of your organization.

   API

      - An application programming interface (API) is a structured method for computer systems to exchange information.
      - APIs can be transactional, returning data as JSON objects.
      - APIs can also facilitate bulk data extraction, returning CSV files.

   WEB SERVICES 
      
      - data is found in private and public data sources and is accessible via a web service.
      - A web service is an API you can call via Hypertext Transfer Protocol (HTTP), the language of the World Wide Web.
      - While a web service is an API, an API does not have to be a web service.
      - If you imagine an API as the door behind which data treasures exist, an API key is what unlocks the door.
      - API providers generate a unique API key for each calling application.
      - Centralized creation and distribution of API keys allow the provider to understand who is using the API and to turn off individual keys' access in the event of abuse.

   WEB SCRAPING

      - Programmatic retrieval of data from a website is known as web scraping.
      - You can use software bots to scrape data from a website.
      - Many modern programming languages, including Python and R, make it easy to create a web scraper.
      - Instead of using an API or a web service, a web scraper reads a web page similar to a browser, such as Chrome, Safari, or Edge.
      - Your web scraper has to account for pagination to ensure that you are not leaving any data behind.

   HUMAN-IN-THE-LOOP

      - There are times when the data you seek exists only in people's minds.
      - Even with all of these data sources, you may still want insight into how customers feel about the services you provide.

   SURVEYS

      - One way to collect data directly from your customers is by conducting a survey.
      - The most simplistic surveys consist of one question and indicate customer satisfaction.
      - Complex survey logic lets you gather additional details as to why a person has a particular opinion.
      - You can design surveys to achieve your data collection goals and your audience.
      - As you design a survey, you want to keep in mind how you will analyse the data you collect.

   SURVEY TOOLS

      - Instead of designing a custom application to collect survey data, several survey products let you design complex surveys without worrying about building a database.
      - Qualtrics is a powerful tool for developing and administering surveys.

   OBSERVATION

      - Observation is the act of collecting primary source data, from either people or machines.
      - Observational data can be qualitative or quantitative. 
      - Collecting qualitative observational data leads to unstructured data challenges.

   SAMPLING

      - Imagine you are doing analytics in an Internet-of-Things environment, in which 800 billion events occur daily.
      - Though it is possible, ingesting and storing 800 billion records is a challenging task.
      - Manipulating 800 billion records takes a lot of computing power.

   WORKING WITH DATA

      - To turn a database design into an operational database ready to accept data, you use the Data Definition Language (DDL) components of SQL.
      - DDL lets you create, modify, and delete tables and other associated database objects.
      - To generate insights, a productive analyst must be comfortable using the Data Manipulation Language (DML) capabilities of SQL to insert, modify, and retrieve information from databases.
      - While DDL manages the structure of a database, DML manages the data in the database.

  DATA MANIPULATION

      - When manipulating data, one of four possible actions occurs:
        1. Create new data.
        2. Read existing data.
        3. Update existing data.
        4. Delete existing data.
      - SQL uses verbs to identify the type of activity a specific statement performs.
      - SELECT, FROM, and WHERE are all reserved words that have specific meanings in SQL.
      - The FROM clause in a query identifies the source of data, which is frequently a database table.
      -Both the SELECT and FROM clauses are required for a SQL statement to return data

   SQL CONSIDERATIONS

      - The keywords in SQL are case-insensitive.
      - However, the case-sensitivity of column names and values depend on the database configuration.
      - Factors that influence convention include database configuration, query efficiency, and how easy it is for people to read and understand the query.

   FILTERING

      - Filtering is a way to reduce the data down to only the rows that you need.
      - To filter data, you add a WHERE clause to a query. 

   FILTERING AND LOGICAL OPERATORS

      - You need to use a logical operator to account for complex filtering needs.
      - The AND operator evaluates the Animal_Type and Weight filters together, only returning records that match both criteria.
      - OR is another frequently used logical operator. 

   SORTING

      - The ORDER BY clause is the component of a SQL query that makes sorting possible.
      - The ASC keyword at the end of the ORDER BY clause sorts in ascending order whereas using DESC with ORDER BY sorts in descending order.
      - Both the ASC and DESC keywords work across various data types, including date, alphanumeric, and numeric.

   DATE FUNCTIONS

      - Storing date information about an event facilitates analysis across time.
      - The most important thing to note is that you have to understand the database platform you are using and how that platform handles dates and times.

   LOGICAL FUNCTIONS

      - Logical functions can make data substitutions when retrieving data.
      - Remember that a SELECT statement only retrieves data.
      - Another way to generate the output in Table 3.10 is by using the IFF logical function.
      - When using logical functions, you need to balance their convenience with the knowledge that you are replacing data from the database with the function's coded values.
      - The ability to do this type of substitution is a real asset when dividing data into categories.

DAY 3

   AGGREGATE FUNCTIONS

      - Summarized data helps answer questions that executives have, and aggregate functions are an easy way to summarize data.
      - Aggregate functions summarize a query's data and return a single value.
      - You can also use aggregate functions to filter data.

   SYTEM FUNCTIONS

      - Each database platform offers functions that expose data about the database itself.
      - One of the most frequently used system functions returns the current date.
      - System functions also return data about the database environment.

   QUERY OPTIMIZATION

      PARAMETRIZATION

      - Whenever a SQL query executes, the database has to parse the query.
      - Parsing translates the human-readable SQL into code the database understands.
      - Parsing takes time and impacts how long it takes for a query to return data.
      - Effective use of parameterization reduces the number of times the database has to parse individual queries.

      INDEXING 

      - When retrieving data from a table, the database has to scan each row until it finds the ones that match the filters in the WHERE clause.
      - The process of looking at each row is called a full table scan.
      - For small tables, full table scans happen quickly. As data volumes increase, scanning the entire table takes a long time and is not efficient.
      - To speed up query performance, you need a database index.
      - A database index works like the index in the back of a book.

      DATA SUBSETS AND TEMPORARY TABLES

      - When dealing with large data volumes, you may want to work with a subset of records.
      - It is possible to create a temporary table to make the data more manageable.
      - Temporary tables can store the results of a query and are disposable.
      - Temporary tables automatically get removed when the active session ends.

      EXECUTION PLAN

      - An execution plan shows the details of how a database runs a specific query.
      - Execution plans are extremely helpful in troubleshooting query performance issues.
      - They provide additional information about how a query is spending its time.
      - Looking at execution plans is an integral part of developing efficient queries.

   DATA QUALITY

      DATA QUALITY CHALLENGES

      DUPLICATE DATA

      - Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system.
      - Humans are primarily responsible for creating duplicate data.
      - System architects work diligently to prevent duplicate data from being created.
      - Having multiple data sources for the same data elements is also a source of duplicate data.

   REDUNDANT DATA

      - While duplicate data typically comes from accidental data entry, redundant data happens when the same data elements exist in multiple places within a system.
      - Frequently, data redundancy is a function of integrating multiple systems.
      - The customer's address in the data warehouse depends on how the ETL jobs function.
      - There are several options for resolving redundant data. 
      - This integrated ETL process takes a delta load approach.
      - The additional ETL logic ensures that the warehouse contains the correct values.
      - Another root cause of data redundancy is an inappropriate database design.

   MISSING VALUES

      - Another issue that impacts data quality is the concept of missing values.
      - Missing values occur when you expect an attribute to contain data but nothing is there.
      - A null is not a space, blank, or other character.
      - Null values present several challenges depending on the tools you use to analyze data.

      INVALID DATA

      - Invalid data are values outside the valid range for a given attribute.
      - ext data is more complex. One thing that leads to invalid character data is an absence of referential integrity within a database. If two tables have a relationship but no foreign keys, the conditions for invalid character data exist. Implementing relationships appropriately reduces the likelihood of invalid character data. As you learned in Chapter 3, implementing referential integrity is an excellent way to improve data quality.

      NONPARAMETIC DATA

      - Nonparametric data is data collected from categorical variables, which you read about in Chapter 2: Understanding Data.
      - Sometimes the categories indicate differentiation, and sometimes they have a rank order associated with them.

      DATA OUTLIERS

      - A data outlier is a value that differs significantly from other observations in a dataset.

      SPECIFICATION MISMATCH

      - A specification describes the target value for a component.
      - A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values.
      - On the other hand, a specification mismatch occurs when data does not conform to its destination data type.

      DATA TYPE VALIDATION

      - Data type validation ensures that values in a dataset have a consistent data type.

DAY 4

   DATA MANIPULATION TECHNIQUES

     RECODING DATA

     - Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis.
     - Recoding groups data into multiple categories, creating a categorical variable.
     - A categorical variable is either nominal or ordinal.
     - Recoding is helpful when you have numeric data you want to analyze by category.
     - Recoding maps the numeric value to the appropriate category.

     DERIVED VARIABES

     - A derived variable is a new variable resulting from a calculation on an existing variable.
     - However, derived variables don't have to be categorical.

     DATA MERGE

     - A data merge uses a common variable to combine multiple datasets with different structures into a single dataset.
     - Merging data improves data quality by adding new variables to your existing data.
     - Additional variables make for a richer dataset, which positively impacts the quality of your analysis.
     - ETL processes commonly append data while transforming data for use in analytical environments.

     DATA BLENDING

     - Data blending combines multiple sources of data into a single dataset at the reporting layer.
     - While data blending is conceptually similar to the extract, transform, and load process in Chapter 3, there is a crucial difference. 

     CONCATENATION

     - Concatenation is the merging of separate variables into a single variable.
     - Concatenation is a highly effective technique when dealing with a source system that stores components of a single variable in multiple columns.
     - Concatenation is also useful when generating address information.

     DATA APPEND 

     - A data append combines multiple data sources with the same structure, resulting in a new dataset containing all the rows from the original datasets.

     IMPUTATION

     - Imputation is a technique for dealing with missing values by replacing them with substitutes.
     - When merging multiple data sources, you may end up with a dataset with many nulls in a given column.

     REDUCTION

     - When dealing with big data, it is frequently unfeasible and inefficient to manipulate the entire dataset during analysis.
     - Reduction is the process of shrinking an extensive dataset without negatively impacting its analytical value.

     DIMENSION REDUCTION

     - One reduction technique is dimensionality reduction, which removes attributes from a dataset.
     - Removing attributes reduces the dataset's overall size.

     NUMEROSITY REDUCTION

     - Another technique is numerosity reduction, which reduces the overall volume of data.
     - One way to reduce the volume of quantitative data is by creating a histogram.
     - You can create a histogram in Python, R, and many visualization-specific tools.
     - When creating a histogram, you can conFigure the width of a rectangle to represent a range of values.
     - Whether you're dealing with one person or 10,000 people's data, histograms are great at reducing the number of data points you have to consider.
     - Another approach to reducing the data is through sampling. 
     - Sampling is a technique that selects a subset of individual records from the initial dataset.
     - The most straightforward technique is a random sample and applies in many cases.


   MANAGING DATA QUALITY

   CIRCUMSTANCES TO CHECK FOR QUALITY

     - Errors during data acquisition, transformation, manipulation, and visualization all contribute to degrading data quality.

     AUTOMATED VALIDATION

     - Many data sources feed analytics environments. While some of these data sources are other computer systems, others depend directly on people.
     - Whether source data is machine- or human-generated, one way to prevent data entry mistakes from adversely impacting data quality is to automate data validation checks.
     - Before automatically validating input data, you need to understand how source data fields map to their corresponding database columns.

     DATA QUALITY DIMENSIONS

     - Six dimensions to take into account when assessing data quality are accuracy, completeness, consistency, timeliness, uniqueness, and validity. 

    DATA QUALITY RULES AND METRIS

    - With an understanding of data quality dimensions, you need to consider how to measure each of them in your quest to improve overall quality. 

    METHODS TO VALIDATE QUALITY

    - Numerous methods are available for validating data quality.
    - These methods range from whether or not your data passes reasonable expectations to statistical methods that look for irregular patterns within your data.
    -  A sound approach to ensuring and improving data quality is by combining these methods appropriately.

DATA ANALYSIS AND STATISTICS

    FUNDAMENTALS OF STATISTICS

    - One key concept is the definition of a population.
    - A population represents all the data subjects you want to analyze.

    COMMON SYMBOLS IN STATISTICS

    - Statistics is all about exploring numbers and performing calculations.

    DESCRIPTIVE STATISTICS

    - Descriptive statistics is a branch of statistics that summarizes and describes data.
    - As you explore a new dataset for the first time, you want to develop an initial understanding of the size and shape of the data. You use descriptive statistics as measures to help you understand the characteristics of your dataset.

    MEASURES OF FREQUENCY

    - Measures of frequency help you understand how often something happens.
    - When encountering a dataset for the first time, you want to determine how much data you are working with to help guide your analysis.

    COUNT

    - The most straightforward way to understand how much data you're working with is to count the number of observations.

DAY 5

  STATISTICS PACKAGES

    IBM SPSS

    - One of the most popular pieces of statistical software is IBM's SPSS package. SPSS is one of the oldest statistical software packages, first released in 1968, but it continues to be used today by many statisticians. Figure 6 shows an example of calculating the correlations between a set of variables using SPSS.

    Stata
    
    - Stata is yet another statistical analysis package that dates back to the 1980s and continues to be updated today. It offers essentially the same features as SPSS and SAS and provides users with both a graphical interface and a command-line interface depending on their personal preference. Stata is less widely used than the more popular SAS and SPSS tools. Figure 8 shows an example of building and visualizing a linear regression model in Stata.

    Minitab

    - The final statistical software package covered on the Data+ exam is Minitab. And, once again, Minitab shares most of the same features as SPSS, SAS, and Stata but fits into the same category as Stata - an older tool that is not widely used today. 

 Machine Learning

    - Moving on from statistics-focused tools, the industry also makes use of a set of graphical tools designed to help analysts build machine learning models without requiring them to actually write the code to do so. These machine-learning tools aim to make machine-learning techniques more accessible. Analysts may still tune the parameters of their models but do not necessarily need to write scripts to do so.

    IBM SPSS Modeler

    - IBM's SPSS Modeler is one popular tool for building graphical machine learning models.
    - Instead of requiring that users write code, it provides an intuitive interface where analysts can select the tasks that they would like the software to carry out and then connect them in a flowchart-style interface.
    - Once the user is satisfied that they've designed the machine learning process, they then run the model and can visually explore the results.

    RapidMiner

    - RapidMiner is another graphical machine learning tool that works in a manner similar to IBM SPSS Modeler.
    - It offers access to hundreds of different algorithms that may be placed in a visually designed machine-learning workflow. 
    - RapidMiner also offers prebuilt analytic templates for common business scenarios.

    Analytics Suites

    - Today, most organizations choose to adopt an analytics suite that provides powerful capabilities that cross all phases of an analytics process.
    - These tools allow analysts to ingest and clean data, perform exploratory statistical analysis, visualize their data, produce models, make predictions, and communicate and report their results.
    - These packages are normally more expensive than the other tools we've discussed, but they also provide an end-to-end environment where all of an organization's analysts and developers may work together on analytics projects.

    IBM Cognos

    - IBM Cognos is an example of one of these integrated analytics suites.
    - It uses a web-based platform to offer analysts within an organization access to their data and is backed by IBM's Watson artificial intelligence capability.
    - The major components of Cognos include the following:
    	- Cognos Connection is a web-based portal that offers access to other elements of the Cognos suite.
     	- Query Studio provides access to data querying and basic reporting tools.
      	- Report Studio offers advanced report design tools for complex reporting needs.
        - Analysis Studio enables advanced modeling and analytics on large datasets.
	- Event Studio provides real-time data monitoring and alerting, allowing business leaders to be immediately notified when certain events take place and/or provide automated responses to those events.
 	- Metric Studio offers the ability to create scorecards for business leaders to quickly analyze key metrics from across the organization.
	- Cognos Viewer allows stakeholders to easily interact with data and analyses prepared using Cognos.

    Microsoft Power BI

    - Power BI is Microsoft's analytics suite built on the company's popular SQL Server database platform.
    - Power BI is popular among organizations that make widespread use of other Microsoft software because of its easy integration with those packages and cost-effective bundling within an organization's Microsoft enterprise license agreement.
    - The major components of Power BI include the following:
      - Power BI Desktop is a Windows application for data analysts, allowing them to interact with data and publish reports for others.
      - The Power BI service is Microsoft's software-as-a-service (SaaS) offering that hosts Power BI capabilities in the cloud for customers to access.
      - Mobile apps for Power BI provide users of iOS, Android, and Windows devices with access to Power BI capabilities.
      - Power BI Report Builder allows developers to create paginated reports that are designed for printing, email, and other distribution methods.
      - Power BI Report Server offers organizations the ability to host their own Power BI environment on internal servers for stakeholders to access.

    MicroStrategy

    - MicroStrategy is an analytics suite that is less well-known than similar tools from IBM and Microsoft, but it does have a well-established user base.
    - MicroStrategy offers many of the same tools as its counterparts, making it easy for users to build dashboards and reports and apply machine learning techniques to their business data.

    Domo

    - Domo is a software-as-a-service (SaaS) analytics platform that allows businesses to ingest their data and apply a variety of analytic and modeling capabilities.
    - It is not a very widely used tool, but knowledge of it is included in the objectives for the Data+ exam.

    Datorama

    - Salesforce Datorama is an analytics tool that focuses on a specific component of an organization's business: sales and marketing.
    - It's not a general-purpose analytics tool but is instead focused on applying machine learning, visualization, and other analytics techniques to the sales and marketing process.

    AWS QuickSight

    - AWS QuickSight is a dashboarding tool available as part of the Amazon Web Services cloud offering.
    - This tool's power comes from the fact that it is available on a pay-as-you-go basis and its integration with the powerful data storage, data warehousing, machine learning, and artificial intelligence capabilities offered by the Amazon cloud.

    Tableau

    - Tableau is arguably the most popular data visualization tool available in the market today.
    - The focus of this tool is on the easy ingestion of data from a wide variety of sources and powerful visualization capabilities that allow analysts and business leaders to quickly identify trends in their data and drill down into specific details.

    Qlik

    - Qlik is another popular SaaS analytics platform, offering access to cloud-based analytics capabilities. The major products offered by Qlik include the following:
       - QlikView is the company's original analytics platform that focuses on providing rapid insights.
       - Qlik Sense is a more advanced platform providing more sophisticated analytics capabilities (at a higher cost, of course!).

    BusinessObjects

    - BusinessObjects is an enterprise reporting tool from SAP that is designed to provide a comprehensive reporting and analytics environment for organizations.
    - One of the strengths of this suite is the ability to integrate BusinessObjects reports with other applications, allowing organizations to integrate analytics into other portions of their workflow.

    Understanding the Business Requirements

    - Reports and dashboards both summarize data for end users, but they distribute those summaries in different ways. 
    - A report is a static electronic or physical document that reflects information at a given point in time.
    - On the other hand, a dashboard is an interactive visualization that encourages people to explore data dynamically.
    - Both reports and dashboards are ideal tools for visualizing data content.

    Understanding Report Design Elements

    - Whenever you give people a tool, it should be approachable and easy to use.
    - When creating a report or a dashboard, you can use existing design principles as guideposts.
    - These design principles, known as the “five Cs” of creating visualizations, will help ensure that your reports and dashboards communicate clearly and efficiently.
    -  When thinking visually, the five Cs are control, correctness, clarity, consistency, and concentration.

    - Control has to do with how you focus the attention of your audience. When someone encounters a dashboard for the first time, one of your goals is to deliver the pertinent information quickly. For instance, if there is a place where people can adjust parameters and have the dashboard respond, use visual highlights to focus attention on this capability.

    - Correctness makes sure that your information is accurate and that there are no spelling mistakes. Pay close attention to correctness when using corporate names and logos. For example, Procter & Gamble is a large consumer goods corporation. Misspelling the company name as “Proctor & Gamble” is embarrassing as it displays a lack of correctness.

    - Clarity refers to selecting the right visualization tool for communicating your message, making sure the visualization is easy to interpret and visually crisp, and using fonts and sizes that are easy to read. For example, consider Figure 3, which uses an ornate font. While the diagram conveys the same information as Figure 2, the font compromises clarity and makes it hard to read.

    - Consistency refers to using the same design and documentation elements throughout your report or dashboard to give your visualization a cohesive and complete feel. Using the same font, page layout, and web page design are all techniques for ensuring consistency.

    - Concentration refers to using visuals to focus your audience's attention on the most relevant information without overwhelming them with details. Concentration, along with clarity and control, helps you focus your audience by reducing clutter and removing unnecessary details. Use a layout that increases concentration and removes distracting visual elements from charts. For example, suppose you are creating a report that summarizes quarterly sales performance. To improve concentration, only show the necessary summary statistics instead of including the raw daily sales data.

#DATA GOVERNENCE WEEK 1

DAY 1

   Understanding Data Governance

       What is meant by governance?

  	- Governance is the manner in which an entity chooses to oversee the control and direction of an area of interest.
   	- When entities grow and increase in complexity, formal governance becomes important.
    	- The formality and structure that governance takes depend on context and intent.
     	- The many domains that have adopted the term governance apply it relative to intent.

       What is meant by data governance?

	- Staff want to find the data they need quickly, and they want it to be high-quality data.
 	- This means the data needs to be accurate and current.
  	- Leaders want data to provide the basis for rich insights that enable timely and informed data-driven decision-making.
   	- To achieve these and other increasingly common business demands, you need some form of data control and accountability in your enterprise.
    	- Quality results require the diligent management of your organization’s data.
     	- Today, when data is managed well, it can drive innovation and growth and can be an enterprise’s most abundant and important lever for success.
      	- Well-managed data can be transformational, and it can support the desirable qualities of a data-driven culture.
       	- Successful data governance also means that data risks can be minimized, and data compliance and regulatory requirements can be met with ease. 


  Data Governance Versus Data Management
 
	- There is often confusion about the difference between data governance and data management.
 	- Data management is the technical implementation of data governance.

  Data Governance versus Information Governance

 	- Data governance generally focuses on data, independent of its meaning.
  	- Information governance is entirely concerned with the meaning of the data and its relationship in terms of outcomes and value to the organization, customers, and other stakeholders.

  The Value of Data Governance

 	- Fundamentally, data governance is driven by a desire to increase the value of data and reduce the risks associated with it. It forces a leap from an ad hoc approach to data to one that is strategic in nature.

  Creating a Data Governance Program

  	- Depending on the level of sophistication and the nature of the business, the design and implementation of a data governance program can vary greatly.
   	- Unfortunately, there’s no one-size-fits-all approach.


  Developing a Data Governance Framework
       
    	- You cannot buy a data governance program off the shelf.
     	- Organizations must implement a program relative to its level of interest, as well as its needs, budget, and capabilities.
        - Regardless of how and to what degree you implement the elements of a data governance program, you’ll need a basic set of guiding concepts and a structure in which to apply them.
	- This is called the data governance framework.

 	Leadership and Strategy

  	- Your data governance program must be aligned with the strategy of the organization.
   	- Data plays a role in many aspects of organizational strategy, including risk management, innovation, and operational efficiencies, so you must ensure there’s a clear alignment between these aspects and the goals of data governance.

	 Roles and Responsibilities

	- Your data governance program will only be possible with the right people doing the right things at the right time.
 	- Every data governance framework includes the identification and assignment of specific roles and responsibilities, which range from the information technology (IT) team to data stewards.

	Policies, Processes, and Standards

  	- At the heart of every data governance program are the policies, processes, and standards that guide responsibilities and support uniformity across the organization.
   	- Each of these must be designed, developed, and deployed.
    	- Depending on the size and complexity of the organization, this can take significant effort.

	Metrics

 	- The data governance program must have a mechanism to measure whether it is delivering the expected results.
  	- Capturing metrics and delivering them to a variety of stakeholders is important for maintaining support, which includes funding. You’ll want to know if your efforts are delivering on the promise of the program.

   	Tools

    	- Fortunately, a large marketplace now exists for tools in support of data governance and management.
     	- These include tools for master data management, data catalogs, search, security, integration, analytics, and compliance.
      	- In recent years, many data science-related tools have made leaps in terms of incorporating ease-of-use and automation.

       Communications and Collaboration

       - With the introduction of data governance and the ongoing, sometimes evolving, requirements, high-quality communications are key.
       - This takes many forms, including in-person meetings, emails, newsletters, and workshops.
       - Change management, in particular, requires careful attention to ensure that impacted team members understand how the changes brought about by the data governance program affect them and their obligations.
    

 Preparing for Data Governance

       - Data governance requires careful treatment, beginning with understanding whether an organization is ready to accept it.
       - Being ready as an organization involves determining the extent to which a data culture exists.
       - As mentioned, any misalignment here is the number one reason data governance program deployments fail.

       What is data culture?

       - Many well-designed projects and initiatives fall flat and fail even though their teams seem to have done everything right.
       - Too often, the work gets deployed into an environment that is either not ready for change or doesn’t have the optimum conditions for success.
       - Culture will always defeat the greatest of strategies almost every time.
       - Effective data cultures support and empower all employees, from the newest intern to the CEO, to access and use meaningful and timely data for their work.
       - Such cultures ensure that employees have attained the skills they need to use data analytics and can make good data-driven decisions.

Maturing the Data Culture

       - If you decide that you need to better prepare the organization for data governance by maturing the data culture, consider these items to start.
       - Help leaders communicate the value of data and model the type of behavior that demonstrates that data is a priority. This must include communicating the positive results of using data.
       - Provide basic tools and education for data use that include manipulating data, analytics, data cleansing, basic query commands, and visualization. Don’t overlook the remarkable capabilities of common applications such as spreadsheets.
       - Recognize that resistance and frustration are part of the journey. Rather than fighting it, find ways to bring comfort and rewards to team members. At a minimum, provide a channel for feedback and positive discussion.

       Defining Data

       - Data has a specific meaning and it’s really important to be clear on the definition, particularly as we start talking about information, knowledge, and insights.

       Why all the focus on data?

       - Data refers to collections of digitally stored units, in other words, stuff that is kept on a computing device.
       - These units represent something meaningful when processed for a human or a computer. 
       - the term data is often used in singular and plural contexts.
       - If we place the word orange in a sentence, such as “An orange is a delicious fruit,” suddenly the data has meaning. 
       - Similarly, if we say, “The t-shirt I purchased cost me R42.00,” then the number 42 now has meaning.

Welcome to The Zettabyte Era

      - A zettabyte is a big number. 
      - It’s 1021, or a 1 with 21 zeros after it.
      - If you own a terabyte drive at home or for school, you’d need one billion of those drives to store just one zettabyte of data.

      From Data to Insight

      - Creating, collecting, and storing data is a waste of time and money if it’s being done without a clear purpose or intent to use it in the future.
      - When we apply information coupled with broader contextual concepts, practical application, and experience, it becomes knowledge.
      - Knowledge is actionable.
      - To go further than this. When we take new knowledge and apply reasoning, values, and the broader universe of our knowledge and deep experiences, we get wisdom.
      - Finally, insight is an outcome that can emerge from knowledge but is best demonstrated through a combination of knowledge and wisdom.

The Role of Data in the 21st Century

      - Since the early days of data processing in the 19th and 20th centuries right through to digital transformation in the 21st century, data has played many important roles.
      - It’s helped us understand the world in completely new ways, improved our ability to make better-informed decisions, and supported our efforts to solve all manner of problems.
      - The value data that has been added over the course of many decades has not remained flat.
      - There’s an argument that data has become the most valuable asset in the world.
      
 Data-Driven Decision-Making
    
      - Perhaps one of the greatest values of data is its ability to help us all make better decisions.

 Data as The New Oil

      - A popular refrain coined by the mathematician Clive Humby in 2006 is that data is the new oil.
      - Just as oil drove and grew economies in the past, data is doing that now. Some have subsequently added that just like oil, data has value but must first be processed to be useful.

  Data Architecture

      - In the same manner, which you can consider the holistic nature of EA in support of the organization’s strategy, data architecture is the manner in which data design and management decisions are being made to align with EA and in turn, with the business.
      - Data architecture is a direct reflection of data governance.
      - An established and functioning data architecture immediately signals that an organization values data, manages it as a critical business asset, and has controls in place to ensure that it aligns with business needs.
      - Indeed, like EA, data architecture is not the exclusive realm of technologists but a cross-organizational responsibility.

  Understanding the Impact of Big Data

      - In fact, we’ve been capturing and storing data in an analog fashion for thousands of years.
      - The Romans, for example, used ledgers to keep track of their various activities across their expansive empire.
      - Fast-forward to the 20th century and the Cold War was instrumental in the technological leaps that resulted in microprocessors and the classical computing we use today.

      The Role of The U.S. Census in The Information Revolution

      - Processing data on some form of computing device has been around since the late 1800s.
      - To count census results, handwritten results were converted to punched holes in cards.
      - The Tabulating Machine Company was later renamed International Business Machines, IBM.

Defining Big Data

      - Big data is structured and unstructured data that is so massive and complex in scale, that it’s difficult and often impossible to process via traditional data management techniques.

      Consequences of Big Data

      - In a time when advertising was mainly billboards and newspapers, it was nearly impossible to know which advertising resulted in a sale.

      Enter the Realm of Smart Data

      - Smart data has emerged as a new term that defines big data that’s been optimally prepared for use to deliver the highest business value.

week 2
day1

 Driving Value Through Data

     - Data isn’t something that just concerns the data analytics team or the information technology department.
     - It’s also not something that is limited to decision-makers and leaders.

     Operations

     - Each business has different needs, and operational functions reflect these specific requirements.
     - Some core functions show up in almost every organization.
     - Consider payroll, order management, and marketing.
     - At the same time, some operational support won’t be required. Not every organization needs its own IT organization, or if it’s a service business, it may not have a warehouse.
     - The performance of operations is often easily quantified by data.

     REPORTING

     - Perhaps the most obvious manifestation of data and information management in any organization is the use of reports.
     - Some say they are the backbone of every business.
     - The content of a report, which can be summarized or detailed, contains data and information in a structured manner.
     - The report may have a discussion of the findings and will conclude with a summary and sometimes a set of recommendations.
     - With so many uses of data and information, the purpose of reporting is largely about improved decision-making.

     IMPROVING OUTCOMES WITH DATA

     - Now that the diverse roles of data have been identified and discussed, it’s useful to understand how data can be leveraged to acquire its maximum value. 
     - It begins with recognizing that data is an organizational asset.
     - This simply means that it’s something that brings economic value to the organization.

     APPROACHING DATA AS AN ASSET

     - An asset is something that is owned by a person, an organization, or a government with the expectation that it can bring some economic benefit. 
     - An asset can be tangible or intangible. Tangible assets are physical things such as inventory, machines, and property. That’s stuff you can see and touch. An intangible asset is the opposite; it’s a non-physical thing like software, copyrights, a brand, and goodwill. Data is an intangible asset.

     - In addition, capturing and valuing assets is required for determining tax obligations and for acquiring loans.

     DATA ANALYTICS

     - Raw data is largely useless.
     - In order to make sense of data, you have to apply specific tools and techniques.
     -  The process of examining data in order to produce answers or find conclusions is called data analytics.
     - Data analytics has four primary types.
     - Data governance concerns itself with, for example, defining the roles, policies, controls, and processes for increasing the quality and value of organizational data.
     - Data management is the implementation of data governance. Without data management, data governance is just wishful thinking. To get value from data, there must be execution.

     GOVERNING DATA

     - Governing data means that some level of control exists to support a related policy.
     - For example, an organization may decide that to reduce risk, there needs to be a policy that requires data to be backed up every day. The control would be the documentation of the process and enforcement of that policy. If, in the review of policy adherence, data wasn’t getting backed up, then you’d quickly know that governance, for whatever reason, was not working.
     - To fully realize the potential of data in your organization means that data must be governed. Any time an organizational resource or asset is left unmanaged, it’s either a recipe for disaster or a missed opportunity. Even a small amount of governance beats no governance every single day.

TRANSFORMING THROUGH DATA

   EXAMINING THE BROADER VALUE OF DATA

     - In small organizations or when a business is first created, only a few systems are used, and team members know the type and location of most of the data that is available.
     - As organizations grow and more systems are employed, eventually no single person knows what data is available and where it is in the enterprise. Without this knowledge, the ability to properly govern your data and leverage its value is greatly hampered. Without deliberate actions, data democratization becomes elusive.
     - Data silos hinder business efficiencies because they reduce collaboration and increase data inconsistencies.
     - In addition, they are a source of risk, including security and regulatory issues.
     - Data governance helps eliminate unnecessary data siloes and makes data discoverable and available whenever and wherever it adds value.
     - Data catalogs, discussed in this chapter, are an essential way that data governance can help solve these limitations.

     
DATA CATALOGS

     - You can take a few approaches to assist your organization so that your team members can find data. One option involves the creation of an enterprise search engine. 
     - It’s certainly possible, but not easy, and will face some limitations such as the discoverability of confidential data that is deliberately siloed.
     - Another, increasingly popular, method of data discoverability is the creation of an enterprise data catalog.
     - Like a store catalog that categorizes products and includes details such as availability and price, a data catalog lists the availability of data sets and includes a wide range of valuable details about that data.
     - A data catalog is more than just a list of all data sets.
     - What makes a data catalog particularly valuable is that it contains data about the data. It’s called metadata.
     - This content can be curated manually and also by automated processes which can acquire it from other sources.
     - A data catalog can contain three types of metadata: technical, business, and operational.
     - For a large number of stakeholders ranging from data analysts to data stewards, a data catalog presents many advantages.
     - Primarily, the ability to find data tops the list.

FROM DATA TO INSIGHTS

     - In a business context, deriving insights is almost the entire point of collecting data.
     - Insight provides a deep understanding of something and is the ultimate positive manifestation of data. 
     - It has the highest value to an organization because it can support decisions and drive actions.
     - If you can’t use your data to make better decisions and drive your organization forward, the data may just be worthless.

DATA MONETIZATION

     - An asset is something owned that has the expectation of delivering value.
     - Unlike tangible assets such as inventory and property, data falls into the same category as assets such as copyrights and software.
     - Intuitively, when something has a high value, it’s likely to be treated differently from things with little value.
     - Without a process to place a price on a data set - called data valuation - the value of a given data set may be highly subjective and may differ considerably between the perspectives of team members.
     - Without this knowledge, it’s much harder to take advantage of the opportunities that some data sets may provide, such as business growth and operational excellence.
     - When data provides an economic benefit to an organization, it's called data monetization.
     - Assuming your organization realizes that data is a strategic corporate asset, you must be intentional in how you manage that asset. 
     - For optimal data monetization, organizations must manage high-value data with the same priority and rigor (and maybe even more) that it treats its most important tangible assets.
  
Data-Driven Decision Making   
   
     - Simply stated, data-driven decision-making (DDDM) is the process of using data to drive business decisions.
     - For DDDM to be really effective and to contribute to high performance, an organization needs a data culture, and specific skills and tools.
     - Critically, there must be leadership support for a culture that advocates decisions rooted in data appreciation and analytics. Executives who demonstrate DDDM are role models for the entire enterprise.
     - In practical terms, it also means enabling team members to have access to data, tools, and training.

Developing a Data Strategy for Improved Results

     - Rather than having a plan and making strategic data-related investments, actions are either complementary to larger initiatives or responsive to some immediate challenge or opportunity.
     - That said, once you make the decision to manage data as the high-value asset it is, you’re going to need a plan. That’s when a data strategy becomes the starting point.
     - Businesses have visions that describe why they exist. They have missions that state what they do. To achieve their visions and missions, a strategy will answer how they will do it.
     - The behavior and outcomes of organizations that have a clear and agreed-upon strategy are often evident. Research shows that they typically execute with efficiency, have higher profits, grow larger, and more frequently hit their other success targets.
     
    - Strategy can apply to processes and assets too. Having a strategy for strategies might be important too.
    - A good data strategy will guide decision-making and resource allocation around data in support of the organization. It will demonstrate and communicate data as a priority and ensure that it is treated in a manner to optimize the success of the organization.

#WEEK 1POWER BI

  DAY 1

  INTRODUCTION

    - Microsoft Power BI is a complete reporting solution that offers data preparation, data visualization, distribution, and management through development tools and an online platform.
    - Power BI can scale from simple reports using a single data source to reports requiring complex data modeling and consistent themes.
    - Use Power BI to create visually stunning, interactive reports to serve as the analytics and decision engine behind group projects, divisions, or entire organizations.

  USE POWER BI

    - Power BI Desktop is the development tool available to data analysts and other report creators.
    - While the Power BI service allows you to organize, manage, and distribute your reports and other Power BI items.

  EXPLORE THE FLOW OF POWER BI

    - There's a common flow when creating reports with Power BI.
    - First, you start with Power BI Desktop to connect to data and create the report. Then you publish the report to the Power BI service and distribute to consumers.
    - The Power BI service also allows you to create high-level dashboards that drill down to reports, and apps to easily group related reports to users in a simple format.

  
BUILDING BLOCKS OF POWER BI

    - The building blocks of Power BI are semantic models and visualizations.
    - Create a semantic model and then use visuals to build a report.

CREATE A SEMANTIC MODEL

    - A semantic model consists of all connected data, transformations, relationships, and calculations.
    - To follow the flow of Power BI, you first connect to data, transform data, and create relationships and calculations to create a semantic model.

    CREATE VISUALIZATIONS IN REPORT

    - In Power BI Desktop, when you create a visualization (also called visual), you add it to the canvas for a report page.
    - Choose your visualizations to build pages in your report.
    - Power BI is a low-code solution, which means that you can "drag and drop" data field directly onto the canvas.
    - One of the most valuable features of Power BI reports is the interactivity between visuals.

    CREATE A DASHBPOARD

    - In the Power BI service, you can also create dashboards after you've published a report.
    - Dashboards consist of a single page made up of tiles.
    - Add tiles to a dashboard by pinning a visual in a report to the dashboard.
    - Tiles aren't interactive like visuals, so when a user interacts with the tile, they go to the underlying report for more information.
    - Dashboards are an excellent way to provide high-level information to consumers.

TOUR AND USE THE POWER BI SERVICE

    ORGANIZE ITEMS WIH WORKSPACES

    - Workspaces are the foundation of the Power BI service.
    - When publishing any report, you must choose a workspace.
    - By default, every user has access to My workspace, which is ideal only for testing.

    EXPLORE SAMPLE REPORTS

    - 
         



     
		  
     









      
          



      
     
     










    
