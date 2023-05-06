**What is the purpose of the ‘with’ statement when opening a file in Python,
and how does it help manage resources while reading and writing files?**

1.When opening a file with *"with"*, it ensures that the file is closed.

**Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python.
Provide examples of when to use each method.**

1. **read() method**:-
   - Reads the entire content of the file into a single string.
2. **readline() method**:-
   - reads a single line from the file and returns it as a string.

**Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’.
blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.**

1. Exception handling is a mechanism in Python that allows you to handle runtime errors or exceptions that may occur during program execution.
2. It involves using the **try, except, and optionally finally blocks** to handle exceptions and ensure proper execution of code.
3. The **try** block is where you place the code that might raise an exception. 
4. If an exception is raised, the **try** block terminates and the exception is caught by the corresponding except block.
5. You can catch specific exceptions by specifying the exception type after the except keyword.
6. The **finally block** is optional and is used to execute code that should always be executed, regardless of whether an exception was raised or not.

