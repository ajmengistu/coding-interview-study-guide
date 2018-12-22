# coding-interview-study-guide
This repository contains the notes I collected to prepare for a coding interview. These notes are based on the popular book: [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850).

## Chapter 1: Arrays & Strings
#### Hash Tables:
* A data structure that maps keys to values for highly efficient look up.

#### ArrayLists & Resizable Arrays

#### StringBuilder
#### Supplemental Topics:
  + ##### Enumeration vs. Iterator
  + ##### Collection Interface 
#### Interview Questions:
  + <b>1.1 Is Unique<b>: 
  + 1.2 Check Permutation:
  + 1.3 URLify:
  + 1.4 Palindrome Permutation:
  + 1.5 One Away:
  + 1.6 String Compression:
  + 1.7 Rotate Matrix:
  + 1.8 Zero Matrix:
  + 1.9 String Rotation:
  
## Chapter 2: LinkedList

#### Interview Questions:
* <b>2.1 RemoveDups</b>: 
  Write code to remove duplicates from an unsorted linked list.
  + <b>2.3 Return Kth to Last</b>: Implement an algorithm to find the kth to last element of a singly linked list.
  + 2.3 Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e. any node but the first and last node) of a singly linked list, given only access to that node.
  + 2.4 Partition: 
  + 2.5 Sum Lists: 
  + 2.6 Palindrome: Check if a linked list is a palindrome.
  + 2.7 Intersection: 
  + 2.8 Loop Detection: Given a circular linked list, return the node at the beginning of the loop.

## Chapter 3: Stacks & Queues:

#### Interview Questions:
  + 3.1 Three in One: Describe how you could use a single array to implement three stacks.
  + 3.2 Stack Min: How would you design a stack which, in addition to push and pop, has a function min, which returns the minimum element? Push, pop and min should all operate in O(1) time.
  + 3.3 Stack of Plates: Imagine a (literal) stack of plates. 
  + 3.4 Queue via Stacks: Implement a MyQueue class which implements a queue using two stacks.
  + 3.5 Sort Stack: Sort a stack such that the smallest items are on the top.
  + 3.6 Animal Shelter: 
 
 ## Chapter 4: Trees & Graphs: 
 
 #### Interview Questions:
  + 4.1 Route Between Nodes: Given a directed graph, find out whether there is a route between two nodes.
  + 4.2 Minimal Tree: Given a sorted (increasing order) array with unique integer elements, create a binary tree with minimal height.
  + 4.3 List of Depths: Given a binary tree, create a linked list of all the nodes at each depth.
  + 4.4 Check Balanced: Check if a binary tree is balanced, defined as a tree such that the heights of the two subtrees of any node never differ by more than one.
  + 4.5 Validate BST: Check if a binary tree is a binary search tree.
  + 4.6 Successor: Find the "next" node (in-order successor) of a given node in a binary search tree. Assume that each node has a link to its parent.
  + 4.7 Build Order: 
  + 4.8 First Common Ancestor: Find the first common ancestor of two nodes in a binary tree. Avoid storing additional nodes in a data structure. Note: This is not necessarily a binary search tree.
  + 4.9 BST Sequence: A binary search tree was created by traversing through an array from left to right and inserting each element. Given a binary search tree with distinct elements, printall possible arrays that could have led to this tree.
  + 4.10 Check Subtree: T1 and T2 are two very large binary trees, with T1 much bigger than T2. Determine if T2 is a subtree of T1.
  + 4.11 Random Node: 
  + 4.13 Paths with Sum: Given a binary tree with each node containing an integer value (positive or negative). Count the number of paths that sum to a given value. The path does not need to start or end at the root or a leaf, but it must go downwards from the parent nodes to child nodes.

## Chapter 5: Bit Manipulation

#### Interview Questions:
  + 5.1 Insertion: 
  + 5.2 Binary to String: Given a real number between 0 and 1 that is passed in as a double, print the binary representation. If the number cannot be represented accurately in binary with at most 32 characters, print "ERROR".
  + 5.3 Flip Bit to Win: You have an integer and you can flip exactly one bit from a 0 to a 1. Find the length of the longest sequence of 1s you could create.
  + 5.4 Next Number: Given a positive integer, print the next smallest and the next largest number that have the same number of 1 bits in their binary representation.
  + 5.5 Debugger: Explain what the following code does: ((n & (n-1) == 0). 
  + 5.6 Conversion: Determine the number of bits you would need to flip to convert integer A to integer B. 
  + 5.7 Pairwise Swap: Swap odd and even bits in an integer with as few instructions as possible. 
  + 5.8 Draw Line: A monochrome screen is stored as a single array of bytes, allowing eight consecutive pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (i.e. no byte will be split across rows). The height of the screen can be derived from the length of the array and the width. Draw a horizontal line from (x1, y) to (x2, y).
  
  ## Chapter 6: Math & Logical Puzzles
  
  #### Interview Questions:
  + 6.1 The Heavy Pill: You have 20 bottles of pills. 19 bottles have 1.0 gram pills, but one has pills of weight 1.1 grams. Given a cale that provides an exact measurement. How would you find the heavy bottle? Note: You can only use the scale once.
  + 6.2 Basketball: You have a basketball hoop and someone says that you can play one of two games. Game 1: You get one shot to make the hoops. Game 2: You get three shots and you have to make two of three shots. If p is the probability of making a particular shot, for which values of p should you pick one game or the other?
  + 6.3 Dominos: There is an 8x8 chessboard in which two diagonally opposite corners have been cut off. You are given 31 dominos, and a single domino can cover exactly two squares. Can you use the 31 dominos to cover the entire board? Prove you answer (by providing an example or showing why it's impossible).
  + 6.4 Ants on a Triangle: There are three ants on different vertices of a triangle. What is the probability of collision (between any two or all of them) if they start walking on the sides of the triangle? Assume that each ant randomly picks a direction, with either direction being equally likely to be chosen, and that they walk at the same speed. Similarly, find the probability of collision with n ants on an n-vertex polygon. 
  + 6.5 Jugs of Water: You have a five-quart jug, and an unlimited supply of water
  + 6.6 Blue-Eyed Island:
  + 6.7 The Apocalypse:
  + 6.8 The Egg Drop Problem:
  + 6.9 100 Lockers:
  + 6.10 Poison:
