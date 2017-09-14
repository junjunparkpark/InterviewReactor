# InterviewReactor
>A thorough study guide to ensure you are ready to interview for any software engineering interview (junior-mid level)
>
>
> Big Thanks to the following, of which this study guide heavily references:
> - Haseeb Qureshi of AppAcademy/AirBnB
> - John Washam of Coding Interview University

## Course Materials :
- [Learning How to Learn - Coursera](https://www.coursera.org/learn/learning-how-to-learn)
- [Princeton Coursera course on algorithms](https://www.coursera.org/course/algs4partI)
- [The Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/ref=sr_1_1?ie=UTF8&qid=1462241467&sr=8-1&keywords=algorithm+design+manual+skiena&tag=charity48-20)
- [Cracking the Coding Interview](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/ref=sr_1_1?ie=UTF8&qid=1462241515&sr=8-1&keywords=cracking+the+coding+interview&tag=charity48-20)
- [Hired in Tech: System Design](https://www.hiredintech.com/system-design)


## Table of Contents
- [Course Materials](#course-materials)
- [Prequisites](#prequisites)
- [Algorithm Complexity / Big O / Asymptomatic Analysis](#algorithmic-complexity--big-o--asymptotic-analysis)
- [Data Structures](#data-structures)
- [Data Structure Algorithms](#data-structure-algorithms)
- [Bit Manipulation](#bit-manipulation)

#Prerequisites:
- Understand C
  - [C Programming Language, Vol. 2](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
- How computers process a program:
  - [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
  - [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)


#Algorithm Complexity / Big O / Asymptomatic Analysis
- [Big O Notation (general quick tutorial) (video)](https://www.youtube.com/watch?v=V6mKVRU1evU)
- [Big O Notation (and Omega and Theta) (video)](https://www.youtube.com/watch?v=ei-A_wy5Yxw&index=2&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)


#Data Structures:
>(Time/Space Complexity and their guarantees)
- Arrays
- Linked List
  - Singly Linked List
  - Doublely Linked List
- [Dynamic array](https://en.wikipedia.org/wiki/Dynamic_array), implemented with a [ring buffer](https://en.wikipedia.org/wiki/Circular_buffer) (use a statically sized array underneath the hood)
- Hash Set
- [Hash Map (with chaining)](https://en.wikipedia.org/wiki/Hash_table#Separate_chaining_with_linked_lists)
- Binary heap (without decrease-key)
  - [Fibonacci heaps](https://en.wikipedia.org/wiki/Fibonacci_heap) and their guarantees
- Binary search tree
  - Self-Balancing BST
- Prefix tree (a.k.a. trie)
- Suffix tree (don’t worry about compression, just build a dumb version)
  - [Ukkonen’s algorithm](https://en.wikipedia.org/wiki/Ukkonen%27s_algorithm)
- An object-oriented [adjacency list](https://en.wikipedia.org/wiki/Adjacency_list) for graphs

#Data Structure Algorithms (Time/Space Complexity and their guarantees):
- Binary search (implement it both iteratively and recursively)
- Randomized quicksort (pay extra attention to the partition subroutine, as it’s useful in a lot of places)
- Mergesort
- Breadth-first search in a graph
- Depth-first search in a graph (augment it to detect cycles)
- Breadth-first/Depth-first search through a matrix
- Tree traversals (pre-order, in-order, post-order)
- Topological sort (using [Tarjan’s algorithm](https://en.wikipedia.org/wiki/Topological_sorting#Depth-first_search))
- Dijkstra’s algorithm ([without decrease-key](http://stackoverflow.com/questions/9255620/why-does-dijkstras-algorithm-use-decrease-key))
- Longest common subsequence (using dynamic programming with matrices)
- Knapsack problem (also dynamic programming)

- Know the [Time/Space complexities of these algorithms and data structures](http://bigocheatsheet.com/)
- Know the difference between [amortized, average](http://stackoverflow.com/a/7335098), and worst-case time guarantees.

Optional:
- Heap sort
- Quickselect
- Median of Medians

#Bit Manipulation:
- Be able to explain what AND, OR, and XOR do.
- Know what a signed integer is.
- Know that there are 8 bits in a byte.
- Know what assembly is (from a high level)
- Get a sense of the basic operations that hardware exposes.
  - This awesome video about the inner workings of the [original Game Boy covers](https://www.youtube.com/watch?v=RZUDEaLa5Nw) just about all you need to know.

Databases:
- SQL Databases:
  - Learn how to design a SQL database schema; it comes up in interviews often.
  - Read about ACID, the CAP theorem, and BASE
    - (you don’t need to memorize the terms, just understand the concepts at a high level.)
  - Understand why joins can become unscalable.
  - Learn the basics of NoSQL databases.
- NoSQL Databases

Caching:
- Read about caches and cache efficiency.
- Know what a cache miss is.
- Know that reading from registers is lightning-fast
- Reading from the various caches is pretty fast
- Reading from memory is slow
- Reading from the hard disk is abysmally slow.
- Read how to implement an LRU cache
  - Write one that gets and sets in worst-case O(1) time.
  - This is a weirdly common interview problem.

Networking:
- [Learn what happens when you type a URL into your browser and press enter](http://igoro.com/archive/what-really-happens-when-you-navigate-to-a-url/comment-page-3/)
- DNS lookups
- Request-response cycle
- HTTP verbs
- TCP vs UDP
- Cookies

General Web Development:
- Learn the standard ways to speed up a slow website:
  - Adding database indices to optimize common queries
  - Better caching
  - Loading front-end assets from a CDN
  - Cleaning up zombie event listeners


