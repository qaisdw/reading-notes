# Big O: Analysis of Algorithm Efficiency

### *Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:*

- **Running Time** (also known as time efficiency / complexity):- 
 The amount of time a function needs to complete.

- **Memory Space** (also known as space efficiency / complexity):-
 The amount of memory resources a function uses to store data and instructions.

**Big O’s role in algorithm efficiency is to describe the Worst Case of efficiency an algorithm can have in performing it’s job.
It specifically looks at the factors mentioned above, which we often refer to as Space and Time. In order to analyze these limiting factors,
we should consider 4 Key Areas for analysis:**

1. Input Size: The input size refers to the size of the data set that the algorithm is operating on. For example, if you're sorting an array of numbers, the input size would be the number of elements in that array. Understanding how the algorithm's performance changes as the input size grows is important for analyzing its efficiency.

2. Units of Measurement: When measuring the efficiency of an algorithm, we use certain units of measurement to describe the time and space complexity. For time, we might use seconds or milliseconds, and for space, we might use bytes or kilobytes.

3. Orders of Growth: The order of growth describes how the algorithm's performance changes as the input size grows. In Big O notation, we use different terms to describe different orders of growth. For example, an algorithm with a constant running time (i.e. its performance doesn't change as the input size grows) would be O(1), while an algorithm with a linear running time (i.e. its performance grows linearly with the input size) would be O(n).

4. Best Case, Worst Case, and Average Case: When analyzing algorithm efficiency, it's important to consider the best case (i.e. the scenario where the algorithm performs the most efficiently), worst case (i.e. the scenario where the algorithm performs the least efficiently), and average case (i.e. the typical scenario in which the algorithm will be used). This helps us understand the algorithm's performance in different scenarios and design algorithms that perform well in the scenarios they'll be used in most often.



# What is a Linked List :-
A Linked List its a type of linear data structure that stores information in a program, kind of like a chain.
Each piece of information is stored in a small piece, called a node, and each node has a pointer to the next piece of information in the chain.
Linked Lists are useful because they can be easily changed or modified, and you can quickly access the information in them by following the pointers.
Linked Lists use dynamic memory allocation, which means that the program decides how much memory to use as it's running.


