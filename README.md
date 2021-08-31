# Python-DSA
Python Data Structure and Algorithms For Cracking Coding Interviews 😎

Algorithms and data structures are fundamental to efficient code and good software design. Creating and designing excellent algorithms is required for being an exemplary programmer. This repository's goal is to demonstrate how to correctly implement common data structures and algorithms in the simplest and most elegant ways.

---
## Contents
`B` - Beginner, `A` - Advanced
* `B` List
<!--

* 
* `B` [Linked List](src/data-structures/linked-list)
* `B` [Doubly Linked List](src/data-structures/doubly-linked-list)
* `B` [Queue](src/data-structures/queue)
* `B` [Stack](src/data-structures/stack)
* `B` [Hash Table](src/data-structures/hash-table)
* `B` [Heap](src/data-structures/heap) - max and min heap versions
* `B` [Priority Queue](src/data-structures/priority-queue)
* `A` [Trie](src/data-structures/trie)
* `A` [Tree](src/data-structures/tree)
  * `A` [Binary Search Tree](src/data-structures/tree/binary-search-tree)
  * `A` [AVL Tree](src/data-structures/tree/avl-tree)
  * `A` [Red-Black Tree](src/data-structures/tree/red-black-tree)
  * `A` [Segment Tree](src/data-structures/tree/segment-tree) - with min/max/sum range queries examples
  * `A` [Fenwick Tree](src/data-structures/tree/fenwick-tree) (Binary Indexed Tree)
* `A` [Graph](src/data-structures/graph) (both directed and undirected)
* `A` [Disjoint Set](src/data-structures/disjoint-set)
* `A` [Bloom Filter](src/data-structures/bloom-filter)

-->

---

## List in Python
Lists are one of the fundamental built-in data types in python. They are collection of items which internally uses Array Data Structures. 

However unlike in languages like C++, . Also, Python Lists allows us to store .
Here are some properties of python lists :
* Python Lists are dynamic in nature, meaning its size grows or shrinks according to data stored or deleted
* It is zero-indexed meaning that the first element has index 0
* It allows duplicate items
* It is ordered in nature
* It allows us to store different data types in a single list itself

### Here's how to declare a list called "A" that has elements 20,40,60,10,20 in the same order
```
A = [20,40,60,10,20]
```
In the above code the,
first element of "A" is 20 and its index is 0, second element of "A" is 40 and its index is 1, third element of "A" is 60 and its index is 2, 
fourth element of "A" is 10 and its index is 3, fifth element of "A" is 20 and its index is 4

### Accessing elements in list
```
A = [20,40,60,10,20]

#accessing the first element 
print(A[0])

#accessing element 60
print(A[2])
```


