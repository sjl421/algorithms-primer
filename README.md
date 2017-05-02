# algorithms-primer
A consolidated collection of resources for you to learn and understand algorithms and data structures easily. 

# Objectives
It is difficult to find consolidated resources on algorithms. 
This repo hopes to gather resources to help one understand algorithms better to prepare 
for technical tests or simply to strengthen your foundation of computer science to help you become a better coder.

# Contributions
Contributions are more than welcome. I cant do everything myself, so I will need all the help I can get. To 
- add a new section or to 
- add on to existing sections, 
- or translate
simply submit a pull request. 

If you are arent sure of how to create a pull request, view the [pull request documentation](https://help.github.com/articles/about-pull-requests/).

# Algorithms Topics
Summaries of the algorithms topics:

### P versus NP
**P** stands for **polynomial time** and **NP** stands for **non-deterministic polynomial time**.
P problems are easily solved by computers, and NP problems are not easily solvable, but if you present a potential solution it’s easy to verify whether it’s correct or not.

Read more here: https://danielmiessler.com/study/pvsnp/#gs.null

### Brute force method
Brute force is simplest way to explore the space of solutions - simply means to go through all solutions, however unlikely they may be, something which is not particularly elegant.

## Dynamic Programming (DP)
**What is DP?**
DP or dynamic optimization basically means to take our problem and somehow break it down into a reasonable number of subproblems so that we can use optimal solutions to the smaller subproblems to give us optimal solutions to the larger ones.

- Allows solve many different types of problems in time O(n)^2 or O(n)^3
- Usually focused on Principle of Optimality, "An optimal solution to any instance of an optimization problem is composed of optimal solutions to its subinstances"

**Read more:**
Competitive Programming book by Steven and Felix Halim
http://www.techiedelight.com/introduction-dynamic-programming/

**Practice here:**
https://www.hackerrank.com/domains/algorithms/dynamic-programming

### Memoization vs Tabulation
Memoization is an optimization technique used primarily to speed up computer programs by storing the results of expensive function calls and returning the cached result when the same inputs occur again. 

Which is better?

### Greedy Algorithms 
In greedy algorithm approach, it builds up a solution piece by piece, where the next piece that offers the most obvious and immediate benefit is chosen.

Algorithms which use the greedy approach:
- Travelling Salesman Problem
- Prim's Minimal Spanning Tree Algorithm
- Kruskal's Minimal Spanning Tree Algorithm
- Dijkstra's Minimal Spanning Tree Alsgorithm
- Graph - Map Coloring
- Graph - Vertex Cover
- Knapsack Problem
- Job Scheduling Problem 

**Common interview questions:**
- 0/1 Knapsack Problem
- Coin change - Given a set of coins and amount, Write an algo­rithm to find out how many ways we can make the change of the amount using the coins given.
- Edit Distance - Given two strings and a set of operations Change (C), insert (I) and delete (D) , find minimum number of edits (operations) required to transform one string into another.
- Longest Common Subsequence

### Knapsack problem with Repetitions
Knapsack problem or the rucksack problem is part of dynamic programming and it is where given a set of items, each with a weight and a value, determine the number of each item to include in a collection so that the total weight is less than or equal to a given limit and the total value is as large as possible. 

**Read more here:**
https://www.youtube.com/watch?v=8LusJS5-AGo (Introduction to Knapsack)
http://cse.unl.edu/~goddard/Courses/CSCE310J/Lectures/Lecture8-DynamicProgramming.pdf

**Practice here:**
https://www.hackerrank.com/challenges/unbounded-knapsack

### Knapsack problem without Repetitions

### Djikstra
Dijkstra's algorithm is an algorithm for finding the shortest paths between nodes in a graph.

### Prim's Algorithm

# Data Structure
## Linked Lists

Introduction to linked lists/ Vectors vs. Linked List: https://www.youtube.com/watch?v=pBrz9HmjFOs (13 minute video)

- Link − Each link of a linked list can store a data called an element.

- Next − Each link of a linked list contains a link to the next link called Next.

- LinkedList − A Linked List contains the connection link to the first link called First.

[insert tutorial point image here]

- Linked List contains a link element called first.

- Each link carries a data field(s) and a link field called next.

- Each link is linked with its next link using its next link.

- Last link carries a link as null to mark the end of the list.

### Advantages/disadvantages of arrays vs linked lists
The linked lists have pointers to the next and the previous item unlike arrays.

**Advs of Linked Lists**
- Dynamic size
- Less expensive to insert/delete
	In arrays, you will have to shifts the items each time an items is inserted/deleted. For linked lists, you just have to change the links to point to the items.

**Disadvs of Linked Lists** 
- We cannot perform a random access of items. We have to access elements sequentially starting from the first node (or at the last node if it is a doubly linked list). So we cannot do binary search with linked lists. In arrays, however, you can simply specify the index of the array to get to the item.
- Extra memory space for a pointer is required with each element of the list.
- Arrays have better cache locality that can make a pretty big difference in performance.

### Applications of a linked list
Implementation of a stack/queue

### Single Linked List 
Item navigation is forward only

//insert single linked list diagrams

### Doubly Linked List
Items can be navigated forward and backward

//insert double linked list diagrams

### Circular Linked List 
In a circular singly linked list, the last node of the list is made to point to the first node.

### Operations on a Linked List
Insertion − Add a new data item in the given collection of data items.

Deletion − Delete an existing data item from the given collection of data items.
Traversal − Access each data item exactly once so that it can be processed.
Searching − Find out the location of the data item if it exists in the given collection of data items.
Sorting − Arranging the data items in some order i.e. in ascending or descending order in case of numerical data and in dictionary order in case of alphanumeric data.

Read more here: 

**Common interview questions**:

- Reverse a Linked List (recursive)
- Reverse a Linked List (iterative)
- Detect Loop in a Linked List
- Given pointers to two single-linked list, find out if they intersect and at which node they intersect
- Merge two unsorted linked list in efficient way
- Delete repeated elements from linked list

**Practice here**: 
https://www.hackerrank.com/domains/data-structures/linked-lists


### Queues

[insert image here: http://www.stoimen.com/blog/wp-content/uploads/2012/06/2.-Queue-Operations.png]
source: http://www.stoimen.com/blog/2012/06/05/computer-algorithms-stack-and-queue-data-structure/ 

Queues is a data structure which follows a First-In-First-Out (FIFO) or Last-In-Last-Out (LILO) methodology. 
One end is always used to insert data (enqueue) and the other is used to remove data (dequeue).

### Stacks

[insert image here: http://www.stoimen.com/blog/wp-content/uploads/2012/06/1.-Stack-Operations.png]
source: http://www.stoimen.com/blog/2012/06/05/computer-algorithms-stack-and-queue-data-structure/

Stacks is a data structure which follows a LIFO (last in, first out) methodology.	

To insert an item, it is called “Push”, to remove an item off is called “Pop”.

### Heaps

### Tree Traversal
### Deque

# Asymptotic notation
## Big-O Notation 
The Big O notation describes the complexity of an algorithm. 
It describes:
- The worst-case scenario, 
- the execution time required/space used
- the upper asymptotic bound

**O(1)**

- Same time regardless of the size of the input data

Coding examples:
- Accessing Array Index (int a = array[0];)
- print "hello";


**O(N)**

Performance will grow linearly and in direct proportion to the size of the input data set.

Coding examples: 
- Traversing an array
- Traversing a linked list
- Linear Search

**O(N)^2**

Performance is directly proportional to the square of the size of the input data set.
This is common with nested iterations over the data set.

These ones are supposed to be the less efficient algorithms if their O(n log n) counterparts are present.

Coding examples: 
- Bubble Sort
- Insertion Sort
-	Selection Sort

**O(2N)**

Performance doubles with each additon to the input data set. The growth curve of an O(2N) function is exponential.

Coding examples: 
recursive calculation of Fibonacci numbers

**O(log n)**

O(log n) is slightly more difficult to explain. 
One good example of a O(log n) problem is when searching up a phone book. Even if the phone book is thick, you would not need to search every name, but you just have to look for the name under the correct alphabet. 

Reducing the problem size with every iteration

Coding examples:
- Binary search
- Finding largest/smallest number in a binary search tree

**O(n log n)**

To better understand it, think of it as O(N) and O(log n). An example of such a notation is the Quick sort when we divide the array into two parts and each time it takes O(N) time to find a pivot element. 

Coding examples:
- Merge Sort
- Heap Sort
- Quick Sort

## Big-Ω (Big-Omega) notation
It describes:
- The worst-case scenario
- the lower asymptotic bound

An example of Big O vs Big Omega of a problem:
http://www.programmerinterview.com/index.php/data-structures/big-o-versus-big-omega-notations/


## Big-θ (Big-Theta) notation
- Both the lower and upper asymptotic bound (tight bound)


# Search
## Linear Search/Sequential Search
- Used when a list of integers is not in any order
- Examines the first element in the list and then examines each "sequential" element in the list until a match is found
- Worst-case performance‎: ‎O(n)
- Best-case performance‎: ‎O(1)

## Binary Search
- Used when in a sorted sequence
- Worst-case performance‎: ‎O(log n)
- Best-case performance‎: ‎O(1)

Assume we have an array of numbers which are arranged in sequence where we want to find out if the number, 17 is within the array. 
[2, 3, 5, 7, 11, 13, 17, 19, 23]

Based on linear search, we have to start at index 0 and progressively go through each element in the array. That would take us 7 searches before we arrive at 17. 
However, based on binary search, 

1. **Set the minIndex and maxIndex** - In this case, let minIndex = 0 and maxIndex = 8.

2. **Set the middle element as the first guess** - The first guess would be value 11, index 4 (since 8/4). Since the array is sorted, we know that if 17 exists, it would be on the right side of the array since 17>11. 

3. **Change the minIndex/maxIndex** - We shift the minIndex to be 5 and maxIndex stays the same at 8. 

4. **Make another guess based on the new minIndex/maxIndex** - Taking the average, our second guess would be at index (8+5)/2 = 6.5 ~ 6, with a value of 17. We have found our integer. 

In conclusion: 
Linear search - 7 searches
Binary search - 2 searches

**Practice here:** 
https://www.hackerrank.com/challenges/binary-search-tree-insertion

**Common interview questions:**
- How to verify whether a binary tree is a binary search tree?

## Red Black Trees
A red-black tree is a binary search tree.

Its properties: 
- Every node is either red or black
- Every leaf (root of tree) (NULL) is black. 
- If a node is red, then both its children are black
- Every simple path from a node to a descendant leaf contains the same number of black nodes

## Naïve Divide and Conquer
## Breadth first search

# Sorting
## Bubble sort
This sorting algorithm is where each item is compared to adjacent items and is exchanged with those that are out of order. Simply put, each item “bubbles” up to the location where it belongs

- Best-case performance‎: ‎O(N)^2
- Worst-case performance‎: ‎O(N)^2

Bubble sort in C : https://www.tutorialspoint.com/data_structures_algorithms/bubble_sort_program_in_c.htm

## Selection sort
This sorting algorithm is where a list of numbers is divided into two parts, the sorted part at the left end and the unsorted part at the right end. Initially, the list is unsorted. 

1. **Select and swap** - Select the smallest element from the unsorted part and swapped with the leftmost element
2. **Continue the process** - This process continues until eventually the whole list becomes sorted

Read more about how it works: https://www.tutorialspoint.com/data_structures_algorithms/selection_sort_algorithm.htm

- Best-case performance‎: ‎O(N)^2
- Worst-case performance‎: ‎O(N)^2

## Insertion sort
## Quick sort
A sorting algorithm which uses divide-and-conquer. 

1. **Pick a pivot** - Given an unsorted list of numbers, pick an element in the list as a pivot

2. **Partitioning** - Rearrange the elements so that all other elements in the list that are less than or equal to the pivot are to its left and all elements in the list are to the pivot's right

3. **Recursively sort** - Recursively sort the elements to the left of the pivot, which must be less than or equal to the pivot) and the elements to the right of the pivot, which must be greater than the pivot

Practice here: 
- https://www.hackerrank.com/challenges/quicksort1
- https://www.hackerrank.com/challenges/quicksort2
- https://www.hackerrank.com/challenges/quicksort3

- Best-case performance‎: ‎O(n log n)
- Worst-case performance‎: ‎O(n)^2

## Merge sort



- Best-case performance‎: ‎O(n log n)
- Worst-case performance‎: ‎O(n log n)

Quiz for sorting: http://quiz.geeksforgeeks.org/quiz-quicksort/

# Recursion
## Towers of Hanoi
# Graph Representation
# Travelling Salesman Problem

#Credits
I myself have learnt a lot while compiling these resources. Thanks to:
- [Hackerrank](https://www.hackerrank.com) 
- https://www.cs.cmu.edu/~avrim/451f09/lectures/lect1001.pdf
- Introduction to the Design & Analysis of Algorithms
- Quora
- Wikipedia
- http://algorithms.tutorialhorizon.com/dynamic-programming-coin-change-problem/
- https://www.tutorialspoint.com
- https://www.youtube.com/watch?v=pBrz9HmjFOs
- http://www.geeksforgeeks.org/linked-list-vs-array/
- https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/
- https://danielmiessler.com
- https://www.khanacademy.org
- 	http://interactivepython.org/

Inspired by:
https://github.com/donnemartin/system-design-primer#step-1-review-the-scalability-video-lecture

# Contact
I would really like to learn from you, so contact me for any issues or questions or ideas.
My github page is [here](https://github.com/stacygohyunsi) and my email is hello@imstacy.com

#License
```
Creative Commons Attribution 4.0 International License (CC BY 4.0)

http://creativecommons.org/licenses/by/4.0/
```





