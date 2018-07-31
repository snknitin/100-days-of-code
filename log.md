# 100 Days Of Code - Log

### Day 0: July 17, 2018 
##### 

**Today's Progress**: Tried out the Burst balloons problem and Trimming a BST

**Thoughts:**  Used DP solution for the first one and a recursive solution to trim a bst into a range of node values

**Link to work:** 


### Day 1: July 20, 2018 
##### 

**Today's Progress**: Tried out the Math related problems
* Ugly number 
* Max points on a Line
* Self Crossing path -  if you go North, West, East, South based on numbers in an array

**Thoughts:**  
* Ugly number is one which has only 2,3,5 as it's prime factors
* Took into account repeated data points, horizontal slopes and parallel lines and single data points
* Two cases, one with just the 4 directions and one with 6 for the next set of north and west to intersect. Done with geometric requirements of distances to cross a path

**Link to work:** 

### Day 2: July 22, 2018 
##### 

**Today's Progress**: Tried out the following problems
* Max binary tree
* Removing duplicates from linked list
* Basic Calculator

**Thoughts:**  Used recursion for first two

* Used Stack based approach for calculator  
  Keep a global running total and a stack of signs (+1 or -1), one for each open scope. The "global" outermost sign is +1.
    - Each number consumes a sign.
    - Each + and - causes a new sign.
    - Each ( duplicates the current sign so it can be used for the first term inside the new scope. That's also why I start with [1, 1] - the global sign 1 and a duplicate to be used for the first term, since expressions start like 3... or (..., not like +3... or +(....
    - Each ) closes the current scope and thus drops the current sign.


**Link to work:** 

### Day 3: July 24, 2018 
##### 

**Today's Progress**: Tried out the following problems
* Minimun number of moves to make all elements equal


**Thoughts:**  
* Using basic math. Since two elements are incremented with each move - sum(arr) - len(arr)x min(arr)


**Link to work:** 


### Day 4: July 25, 2018 
##### 

**Today's Progress**: Design Patterns for Python

**Thoughts:**  Learnt about different types of design patterns and how to use them based on context and scenarios. Blogged about it

**Link to work:** https://medium.com/@snk.nitin/design-patterns-and-where-to-find-them-ab57aef6f62a


### Day 5: July 29, 2018 
##### 

**Today's Progress**: Coding practice
* Foursum
* Longest vaid parenthesis
**Thoughts:**  

**Link to work:** 


### Day 5: July 29, 2018 
##### 

**Today's Progress**: Coding practice
* N queens
**Thoughts:**  

**Link to work:** 


