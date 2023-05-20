
# Scope, Big O notation and Rolling Dice


## Variable Scope in Python:


Variable scope refers to where variables are defined and can be accessed within a program.
In Python, we have two types of variable scope: local and global.

1. Local Scope: Variables defined inside a function are local variables and can only be accessed within that function.
They are created when the function is called and destroyed when the function completes.

2. Global Scope: Variables defined outside of any function have global scope and can be accessed from anywhere within the program.
They exist as long as the program is running.

```python
      def my_function():
          local_variable = 10  # Local variable
          print(local_variable)

      my_function()
      # Output: 10

      global_variable = 5  # Global variable

      def another_function():
          print(global_variable)

      another_function()
      # Output: 5
```

## Global and Nonlocal Keywords:

1. Global Keyword: The global keyword allows us to modify a global variable inside a function.
By using the global keyword, we can access and modify the global variable instead of creating a new local variable with the same name.

2. Nonlocal Keyword: The nonlocal keyword is used to access and modify a variable from an outer nested function.
It is used when we have nested functions, and we want to update a variable from the enclosing function.

We use the global keyword when we want to modify a global variable within a function,
and the nonlocal keyword when we want to update a variable from an outer nested function.

## Purpose of Big O Notation:

Big O notation is a way to measure and describe the efficiency of an algorithm in terms of its time and space complexity.
It helps us understand how an algorithm's performance scales with the input size. It allows us to compare
different algorithms and make informed decisions about which one to use for a specific problem.

The importance of Big O notation lies in its ability to provide a standardized way of analyzing and comparing algorithms.
It helps us identify the most efficient algorithm for a given task, optimize our code, and predict how our program will perform as the input size increases.
By understanding the Big O notation, we can write more efficient and scalable code.

Simulating a Dice Roll and Calculating Probability:

To simulate a dice roll using Python, we can use the random module, which provides functions for generating random numbers.
We can use the `randint()` function to generate a random number between 1 and 6, simulating a dice roll.

To calculate the probability of rolling a specific number, such as 6, over a large number of trials, we can write a loop to simulate multiple dice rolls.
We keep track of the number of times the desired number appears and divide it by the total number of trials to get the probability.

Here's an example:
```python
      import random

      def simulate_dice_roll():
          return random.randint(1, 6)

      def calculate_probability(trials, target_number):
          count = 0
          for _ in range(trials):
              if simulate_dice_roll() == target_number:
                  count += 1
          probability = count / trials
          return probability

      num_trials = 1000000
      target = 6

      probability = calculate_probability(num_trials, target)
      print(f"The probability of rolling a {target} is: {probability}")
```
This code simulates 1,000,000 dice rolls and calculates the probability of rolling a 6.
By dividing the count of occurrences of the target number by the total number of trials, we get the probability.

 
