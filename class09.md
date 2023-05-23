# 1. Dunder methods :-


The purpose of dunder methods in Python is to define special behavior for objects of a class. Dunder methods,
also known as magic methods or special methods, are surrounded by double underscores (i.e., "__method__").
They allow you to customize the behavior of your objects, enabling you to define how they should respond to different operations,
such as arithmetic operations, comparisons, and string representations.


#### **Example :-**

```python

class Node : 
    def __init__(self , data):
        self.data = data
        self.next = None 

```


# 2. Links to an external site.ethical issue concerning the use of developers’ work.

The main ethical issue raised in the video was the unauthorized use of developer's work, specifically code plagiarism.
The AI guru allegedly took existing open-source code, rebranded it as their own, and sold it without giving credit to the original developers.
To avoid such ethical issues, it is important to respect intellectual property rights, give proper attribution, seek permissions, and develop original work.



# 3. Python statistics module:-


The Python **statistics** module is part of the standard library and offers convenient functions for statistical calculations.
One commonly used function is **mean()**, which calculates the average of a list of numbers. Additional functions like **median()**, **mode()**, **stdev()**,
and **variance()** compute the median, mode, standard deviation, and variance, respectively. By utilizing these functions, the
**statistics** module streamlines statistical operations, making it easier to analyze and manipulate data in Python.

#### **Example :-**

```python

import statistics

data = [2, 4, 6, 8, 10]

average = statistics.mean(data)
print(average)  # Output: 6.0

```
