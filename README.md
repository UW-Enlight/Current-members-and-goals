# Current-members-and-projects
Repo to use to display the orgs current projects, and goals for those projects. As well as a repo for new members to practice git by adding their name to the member list.

# (Fall 2017) Project 1:

# (Fall 2017) Project 2:

# Interview Questions and their Answers:
First some general resources...<br>
<a href="https://github.com/cassidoo/getting-a-gig">This github repo has a ton of great info and links.</a><br>
<a href="http://rosettacode.org/wiki/Rosetta_Code">The wikipedia of coding algorithms. A great way to practice your algo programming</a><br>
<a href="https://github.com/h5bp/Front-end-Developer-Interview-Questions">Web development specific questions</a>

# Places to go practice:
<a href="https://leetcode.com/">https://leetcode.com/</a><br>
<a href="https://www.hackerrank.com/">https://www.hackerrank.com/</a><br>
<a href="https://www.codecademy.com/">https://www.codecademy.com/</a><br>
<a href="https://www.codechef.com/">https://www.codechef.com/</a><br>
<a href="https://code.google.com/codejam/">https://code.google.com/codejam/</a><br>

## Come up with an algorithm that will return the 'n'th element in the fibonacci sequence.
<br>Example input:  0, 1, 2, 3, 4, 5...
<br>Example output: 1, 1, 2, 3, 5, 8...
<br>For a example solution, <a href="https://github.com/UW-Enlight/Current-members-and-goals/blob/master/fib.py">Look here..</a> note this is not the only way to do this...
Follow up questions: 
- Can you do it a different way?
- Is your way the most efficient?

## Come up with and algorithm to compress an input of characters.
<br>For example, if I give you aaaaaaaaabbbbbbaaaaaccccccccfffffhhhhhh
<br> how would you compress that string?
<br> Does your implementation have a worst case senario? How does it handle it?
<br> What is the big O run time of your solution?
<br>Example solution can be found <a href="https://github.com/UW-Enlight/Current-members-and-goals/blob/master/compression.java">Here</a>

## Explain the differance between a Java Abstract class, and a Java Interface.
<a href="http://stackoverflow.com/questions/1913098/what-is-the-difference-between-an-interface-and-abstract-class">See the first and second answer here.</a>

## Define the following terms, and their give and example of when you would use them.
- Polymorphism
- Inheritance
- Autoboxing
- struct vs object
- Interface
- static
- public vs private
- final / const
- big O notation
- Assembly vs machine code vs programming language
- what actually happens with an import / #include / using statement?

It will be left to the group / you to come up with or google the definitions.

## How would you design a stack which, in addition to push and pop, also has a function min which returns the minimum element? Push, pop and min should all operate in O(1) time.

The answer that comes to mind first is likely having a minValue integer that stores the current minimun value in the stack but if the minimum value is popped off of the stack then you would have to search the stack again for the new minimum value.  The way to get around this is to store minimum values in a stack alongside your original stack. The way this works is: when you push to your stack check it against the minValue int. If it is less than or equal to the minValue then also push it to your minimum value stack. When you pop from the stack, check against minValue and if it is equal to the minvalue pop it off of the minimum value stack as well.

I may add an implememtation to this later.

## Using a Stack data structure, create a Queue (FIFO). Then do the reverse, using a Queue (FIFO) create a Stack.
- Follow up, how many data structures do you need for each?
- What are the normal big O run times for the operations, and what are they in your implementation? Can yours be made better?
- Are there any advantages or disadvantages to your way? Are there any advantages or disadvantages to implementing a data structure like this (using a different one)?
- <a href="http://stackoverflow.com/questions/688276/implement-stack-using-two-queues">Queue using stacks here</a>
- <a href="http://stackoverflow.com/questions/69192/how-to-implement-a-queue-using-two-stacks">Stack using queues here</a>

## A non-technical question often asked in interviews, "How do you stay on top of or learn new technologies in our industry?" This is a tough question becuase they want you to give some variety of things that you are learning. Languages, Tools, Frameworks, etc... So lets build a list below of places that you can go to, to learn new things in computer science. (I'm going to post the obvious ones so that you guys have to do some digging)
- Reddit (note: in an interview it is OK to say you learn stuff on reddit, and I hope you do!)
- github.com/trending (a neat place to see what people are working on)
- class (note: this is not really a good answer.... in class you usually learn old information that is the foundation for newer stuff.
- lynda.com (note: UW gives us all a free account! go use it!)

## Given an unordered array of integers, find the mode element (if there are mutiple, choose how to handle it) and return it. Your solution should be very memory efficient, and have reasonable running time.

## Given a single linked list, take the elements and swap every pair. Example input and ouput below
 - Input:  1-2-3-4-5-6-7-8-9-0
 - Output: 2-1-4-3-6-5-8-7-0-9
 
 ## Given a single linked list, implement each of the sort algorithms below.  Comment on their efficiency and how it would be made better or worse if you instead had a double linked list.
  - bubble sort
  - insertion sort
  - quick sort
  - merge sort
  
  ## Write a function hasDuplicates that takes a single parameter, an unsorted int array of size n.  Return true if the array contains duplicate values, and return false if all values in the array are unique.

Example test cases
Input:  [1, 2, 3, 2, 1, 2, 3, 2, 1]
Output: true

Input:  [1, 3, 5, 7, 9, 2, 4, 6, 8, 0]
Output: false
