# coding-interview-study-guide
 
This repository contains the notes I collected to prepare for a coding interview. These notes are based on the popular book: [Cracking the Coding Interview, 6th Edition](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850). 

## Chapter 1: Arrays & Strings
<details>
 <summary>Notes</summary>
 
 #### Hash Tables: A data structure that maps keys to values for highly efficient look up.

#### ArrayLists & Resizable Arrays   
 
#### StringBuilder 
#### Supplemental Topics:
  + ##### Enumeration vs. Iterator 
  + ##### Collection Interface 
 </details> 

 #### Interview Questions:
 <details>
 <summary>Interview Questions</summary>
 
  + <b>1.1 Is Unique<b>: 
  + 1.2 Check Permutation:
  + 1.3 URLify:
  + 1.4 Palindrome Permutation:
  + 1.5 One Away: 
  + 1.6 String Compression:
  + 1.7 Rotate Matrix:
  + 1.8 Zero Matrix:
  + 1.9 String Rotation:
 </details> 
 
  
## Chapter 2: LinkedList
<details>
<summary>Interview Questions</summary>
 
  * 2.3 Return Kth to Last: Implement an algorithm to find the kth to last element of a singly linked list.
  * 2.3 Delete Middle Node: Implement an algorithm to delete a node in the middle (i.e. any node but the first and last node) of a singly linked list, given only access to that node.
  * 2.4 Partition: 
  * 2.5 Sum Lists: 
  * 2.6 Palindrome: Check if a linked list is a palindrome.
  * 2.7 Intersection: 
  * 2.8 Loop Detection: Given a circular linked list, return the node at the beginning of the loop.
</details>
 
## Chapter 3: Stacks & Queues:
<details>
 <summary>Interview Questions</summary>
 
  + 3.1 Three in One: Describe how you could use a single array to implement three stacks.
  + 3.2 Stack Min: How would you design a stack which, in addition to push and pop, has a function min, which returns the minimum element? Push, pop and min should all operate in O(1) time.
  + 3.3 Stack of Plates: Imagine a (literal) stack of plates. 
  + 3.4 Queue via Stacks: Implement a MyQueue class which implements a queue using two stacks.
  + 3.5 Sort Stack: Sort a stack such that the smallest items are on the top.
  + 3.6 Animal Shelter: 
 </details>
 
 ## Chapter 4: Trees & Graphs: 
 <details>
 <summary>Interview Questions</summary>
 
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
 </details>
  
## Chapter 5: Bit Manipulation
<details>
 <summary>Interview Questions</summary>
 
  + 5.1 Insertion: 
  + 5.2 Binary to String: Given a real number between 0 and 1 that is passed in as a double, print the binary representation. If the number cannot be represented accurately in binary with at most 32 characters, print "ERROR".
  + 5.3 Flip Bit to Win: You have an integer and you can flip exactly one bit from a 0 to a 1. Find the length of the longest sequence of 1s you could create.
  + 5.4 Next Number: Given a positive integer, print the next smallest and the next largest number that have the same number of 1 bits in their binary representation.
  + 5.5 Debugger: Explain what the following code does: ((n & (n-1) == 0). 
  + 5.6 Conversion: Determine the number of bits you would need to flip to convert integer A to integer B. 
  + 5.7 Pairwise Swap: Swap odd and even bits in an integer with as few instructions as possible. 
  + 5.8 Draw Line: A monochrome screen is stored as a single array of bytes, allowing eight consecutive pixels to be stored in one byte. The screen has width w, where w is divisible by 8 (i.e. no byte will be split across rows). The height of the screen can be derived from the length of the array and the width. Draw a horizontal line from (x1, y) to (x2, y).

 </details>
 
  ## Chapter 6: Math & Logical Puzzles  
  <details>
 <summary>Interview Questions</summary>
 
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
</details>

## Chapter 7: Object Oriented Programming
<details>
 <summary>Interview Questions</summary>
 
  + 7.1 Deck of Cards: Design the data structure for a generic deck of cards. Explain how you would subclass the data structure to implement blackjack.
  + 7.2 Call Center:
  + 7.3 Jukebox: Design a musical jukebox using object-oriented principles
  + 7.4 Parking Lot: Design a parking lot using object-oriented principles
  + 7.5 Online Book Reader: Design the data structure for an online book reader system.
  + 7.6 Jigsaw: Implement an NxN jigsaw puzzle. Design the data structure and explain an algorithm to solve the puzzle. Assume that you have a fitswith method, which when passed two puzzle edges, reutrns true if the two edges belong together.
  + 7.7 Chat Server: Explain how you would design a chat server. In particular, provide details about the varaious backend components, classes, and methods. What would be the hardest problems to solve?
  + 7.8 Othello: Othello is played as follows: Each Othello piece is white on one side and black on the other. When a piece is surrounded by its opponents on both the left and right sides, or both the top and bottom, it is said to be captured and its color is flipped. On you turn, you must capture at least one of your opponent's pieces. The game ends when either user has no more valid moves. The win assigned to the person with the most pieces. Implement the object oriented design for Othello.
  + 7.9 Circular Array: Implement a CircularArray class that supports an array-like data structure which can be efficiently rotated. If possible, the class should use a generic type (also called a template), and should support iteration via the standard for each loop (for (Obj 0 : circularArray) notation.
  + 7.10 Minesweeper:
  + 7.11 File System:
  + 7.12 Hash Table: Design and implement a hash table which uses chaining (linked lists) to handle collisions.
</details>

## Chapter 8: Recursion & Dynamic Programming
<details>
 <summary>Interview Questions</summary>
 
  + 8.1 Triple Step: A child is running up a staircase with n steps and can hop either 1 step, 2 steps, or 3 steps at a time. Implement a method to count how many possible ways the hcild can run up the stairs.
  + 8.2 Robot in a Grid: Imagine a robot sitting on the upper left corner of grid with r rows and c columns. The robot can only move in two directions, right and down, but certain cells are "off-limits" such that the robot cannot step on them. Design an algorithm to find a path for the robot from the top left to the bottom right. 
  + 8.3 Magic Index: A magic index in an array A[0 ... n-1]  is defined to be an index such that A[i] = i. Given a sorted array of distinct integers, write a method to find a magic index, if one exists, in array A. 
  + 8.4 Power Set: Write a method to return all subsets of a set.
  + 8.5 Recursive Multiply: Write a recursive function to multiply two positive integers without using * operator. You can use addition, subtraction, and bit shifting, but you should minimize the number of those operations. 
  + 8.6 Towers of Hanoi: In the classic problem of the Towers of Hanoi, you have 3 towers and N disks of different sizes which can slide onto any tower. The puzzle starts with disks sorted in ascending order of size from top to bottom (i.e., each disk sits on top of an even larger one). You have the following constraints:
  * Only one disk can be moved at a time.
  * A disk is slid off the otp of one tower onto another tower.
  * A disk cannot be placed on top of a smaller disk.
  * Write a program to move the disks from th efirst tower to the last usings stacks.
  + 8.7 Permutations without Dups: Write a method to compute all permutations of a string of unique characters.
  + 8.8 Permutations with Dups: Write a method to compute all permutations of a string whose characters are not necessarily unique. The list of permutations should not have duplicates.
  + 8.9 Parens: Implement an algorithm to print all valid (e.g., properly opened and closed) combinations of n pairs of parentheses.
  + 8.10 Paint Fill: Implement the 
  + 8.11 Coins:
  + 8.12 Eight Queens:
  + 8.13 Stack of Boxes:
  + 8.14 Boolean Evaluation:
</details>

## Chapter 9: System Design & Scalability
<details>
 <summary>Interview Questions</summary>
 
  + 9.1 Stock Data: Imagine you are building some sort of service that will be called by up to 1,000 client applications to get simple end-of-day stock price information (open, close, high, low). You may assume that you already have the data, and you can store it in any format you wish. How would you design the client-facing service that provides the inforomation to client applications? You are responsible for the development, rollout, and ongoing monitoring and maintenance of the feed. Describe the different methods you considered and why you would recommend your approach. Your service can use any technologies you wish, and can distribute the information to the client application in any mechanism you choose.
  + 9.2 Social Network: How would you design the data structure for a very large social network like Facebook or LinkedIn? Design how you would design an algorithm to show the shortest path between two people?
  + 9.3 Web Crawler: If you were designing a web crawler, how would you avoid getting into infinite loops?
  + 9.4 Duplicate URLs: You have 10 billion URLs. How would you detect the duplicate documents? In this case, assume "duplicate" means the URLs are identical.
  + 9.5 Cache: Imagine a web server for a simplified search engine. This systemm has 100 machines to respond to search queries, which may then call out using ```processSearch(string query)``` to another cluster of machines to actually get the result. The machine which responds to a given query is chosen at random, so you cannot guarantee that the same machine will always respond to the same request. The method ```processSearch``` is very expensive. Design a caching mechanism for the most recent queries. Be sure to explain how you would update the cache when data changes.
  + 9.6 Sales Rank: A large eCommerce wishes to list the best-selling products, overall and by category. For example, one product might be the #1056th best-selling product overall but the #13th best-selling product under "Sports Equipment" and the #24th best-selling product under "Safety". Describe how you would design this system?
  + 9.7 Personal Financial Manager: Explain how you would design a personal financial manager (like mint.com). This system would connect to your bank accounts, analyze your spending habits, and make recommendations.
  + 9.8 Pastebin: Design a system like pastebin, where a usercan enter a piece of text and get a randomly generated URL to access it.  
</details>

## Chapter 10: Sorting and Searching
<details>
 <summary>Interview Questions</summary>
 
  + 10.1 Sorted Merge: Given two sorted arrays, A and B, where A has a large enough buffer at the end to hold B. Write a method to merge B into A in sorted order.
  + 10.2 Group Anagrams: Sort an array of strings so that all the anagrams are next to each other.
  + 10.3 Search in Rotated Array: Given a sorted array of n integers that has been rotated an unkown number of times, write code to find an element in the array. Assume that the array was orginally sorted in increasing order. 
  + 10.4 Sorted Search, No Size: 
  + 10.5 Sparse Search: Given a sorted array of strings that is interspersed with empty strings, write a method to find the location of a given string.
  + 10.6 Sort Big File: Imagine you have a 20 GB file with one string per line. Explain how you would sort the file.
  + 10.7 Missing Int: 
  + 10.8 Find Duplicates:
  + 10.9 Sorted Matrix Search:
  + 10.10 Rank from Stream:
  + 10.11 Peaks and Valleys:
</details>

## Chapter 11: Testing
<details>
 <summary>Interview Questions</summary>
 
  + 11.1 Mistake: Find the mistake(s) in the following code:
  + 11.2 Random Crashes:
  + 11.3 Chess Test:
  + 11.4 No Test Tools: How would you load test a webpage without using any test tools?
  + 11.5 Test a Pen: How would you test a pen?
  + 11.6 Test an ATM: How would you test an ATM in a distributed banking system?
</details>

## Chapter 13: Java
<details>
 <summary>Interview Questions</summary>
 
  + 13.1 Private Constructor: In terms of inheritance, which is the effect of keeping a constructor private?
  + 13.2 Return from Finally: In Java, does the finally block get executed if we insert a return statement inside the try block of a try-catch-finally?
  + 13.3 Final, etc.: What is the difference between final, finally, and finalize?
  + 13.4 Generics vs. Templates: Explain the difference between templates in C++ and generics in Java.
  + 13.5 TreeMap, HashMap, LinkedHashMap: Explain the differences between TreeMap, HashMap, and LinkedHashMap. Provide an example of when each one would be best.
  + 13.6 Object Reflection: Explain what object reflection is in Java and why it is useful.
  + 13.7 Lambda Expressions: There is a class Country that has methods getContinent() and getPopulation(). Write a funciton 
  ```int getPopulation(List<Country> countries, String continent)``` that computes the total population of a given continent, given a list of all countries and the name of a continent.
  + 13.8 Lambda Random: Using Lambda expressions, write a function ```List<Integer> getRandomSubset(List<Integer> list)``` that returns a random subset of arbitrary size. All subsets (including the empty set) should be equally likely to be chosen.
</details>

## Chapter 14: Databases
<details>
 <summary>Interview Questions</summary>
  
  + Questions 1 through 3 refer to the database schema at the end of the chapter. Each apartment can have multiple tenants, and each tenant can have multiple apartments. Each apartment belongs to one building, and each building belongs to one complex. 
  + 14.1 Multiple Apartments: Write a SQL query to get a list of tenants who are renting more than one apartment.
  + 14.2 Open Requests: Write a SQL query to get a list of all buildings and the number of open requests (Requests in which status equals 'Open').
  + 14.3 Close All Requests: Building #11 is undergoing a major renovation. Implement a query to  close all requests from apartments in this building.
  + 14.4 Joins: What are the different types of joins? Please explain how they differ and why certain types are better in certain situations.
  + 14.5 Denormalization: What is denormalization? Explain the pros and cons?
  + 14.6 Entity-Relationship Diagram: Draw an entity-relationship diagram for a database with companies, people, and professionals (people who work for companies). 
  + 14.7 Design Grade Database: Imagine a simple database storing information for student's grades. Design what this database might look like and provide a SQL query to return a list of the honor roll students (top 10%), sorted by their grade point average.
</details>

## Chapter 15: Threads & Locks:
<details>
 <summary>Interview Questions</summary>
  
  + 15.1 Thread vs Process: What's the difference between a thread and a process?
  + 15.2 Context Switch: How would you measure the time spent in a context switch?
  + 15.3 Dining Philosophers: In the famous dining philosoper problem, a bunch of philosophers are sitting around a circular table with one chopstick between each of them. A philosopher needs both chopsticks to eat, and always picks up the left chopstick before the right one. A deadlock could potentially occur if all the philosophers reached for the left chopstick at the same time. Using threads and locks, implement a simulation of the dining philosopher problem that prevents dead-locks.
  + 15.4 Deadlock-Free Class: Design a class which provides a lock only if there are no possible deadlocks.
  + 15.5 Call In Order: Suppose we have the following code: <br />
  ```
  public class foo {
    public Foo(){ ... }
    public void first() { ... }
    public void second() { ... }
    public void third() { ... }
  }
  ```
  The same instance of Foo will be passed to three different threads. ThreadA will call first, threadB will call second, and threadC will call third. Design a mechanism to ensure that first is called before second and second is called before third.
  + 15.6 Synchronized Methods: You are given a class with synchronized method A and a normal method B, If you have two threads in one instance of a program, can they execute A at the same time? Can they execute A and B at the same time?
  + 15.7 FizzBuzz: In the classic problem FizzBuzz, you are told to print the numbers from 1 to n. However, when the number is divisible by 3, print "Fizz". When it is divisible by 5, print "Buzz". When it is divisible by 3 and 5, print "FizzBuzz". In this problem, you are asked to do this in a multithreaded way. Implement a multithreaded version of FizzBuzz with four threads. One thread checks for divisiblity of 3 and prints "Fizz". Another thread is responsible for divisibility of 5 and prints "Buzz". A third thread is responsible for divisibility of 3 and 5 and prints "FizzBuzz". A fourth thread does the numbers. 
</details>

## Leet Code Top Interview Questions (Easy)
<details>
 <summary>Array</summary>

* 1.1 Remove Duplicates from Sorted Array
* 1.2 Best Time to Buy and Sell Stocks
* 1.3 Rotate Array
* 1.4 Contains Duplicate
* 1.5 Single Number
* 1.6 Intersection of Two Arrays II
* 1.7 Plus One
* 1.8 Move Zeroes
* 1.9 Two Sum
* 2.0 Valid Sudoku
* 2.1 Rotate Image
</details>

<details>
 <summary>Strings</summary>

* 1.1 Reverse String
* 1.2 Reverse Integer
* 1.3 First Unique Character in a String
* 1.4 Valid Anagram
</details>

## Programming Interview Exposed 
<details>
 <summary>Reading Notes</summary>
 
### Preface:
You’ll get as much out of this book as you put into it. Take some time trying to work through the problems before you read the solutions. Deliberate practice.
If you work on learning to solve not just the specific problems we present, but the types of problems we present, you’ll be able to handle anything they throw at you in an interview
Learning by watching is never as effective as learning by doing. If you want to get the most out of this book, you will have to work out the problems yourself. 
After you read a problem, put the book down and try to work out the solution.
### Introduction:
Landing a great programming job isn’t a matter of luck; it’s a matter of preparation. Software firms want to hire great programmers who can work well with others to successfully produce great products.
Programming interview do not assess essential skills such as: communicating, teamwork, architecture, management of large codebases, discipline to consistently produce reliable code on schedule; and the ability to tackle a large projects.
How to use the book: 
Preparation is the key to mastering the programming interview process.
Don’t skip or gloss over the material you don’t understand.
### Chapter 1: Before the Search:
The best programmers are passionate about their work.
Know yourself: know they type of programmer you want to be.
Do well in school: Although grades aren’t everything, they are one measure that companies use to rank new graduates with little job experience.
### Chapter 2: The Job Application Process:
When an offer is made, do not accept it immediately. Give yourself time to consider it.
Look over the offer, try to negotiate a better deal, no matter what the recruiter says.
Recruiter’s job is to do everything necessary to get you to accept the offer at the lowest possible salary.
### Chapter 3: Approaches to Programming Problems:
How a candidate performs during the programming interviews is the main determinant of whether an offer is made.
Many of the questions are designed to take up to an hour to solve, so don’t get frustrated if you don’t see the answer right away. 
Note: These problems are hard! Some of the questions are designed to see how you handle a problem when you don’t immediately see the solution. 
### The Process
The point of the coding questions is to determine how well you can code. It’s the most important part of the interview.
Show the interviewer that you understand the underlying concepts, not that you’ve managed to memorize the answer to a programming puzzle.

### Solving the Problems: (discussion between you and the interviewer)
1. Make sure you understand the problem. Ask the right clarifying question.
2. When you understand the question, try a simple example.
3 a. Find the brute force solution.
3 b. Focus on the algorithms and data structures you will use to solve the problem
4. After you figure out your algorithm & how you can implement it, explain your solution to the interviewer. 
5. While you code, explain what you’re doing. Narrate your code.
6. Ask questions when necessary.
7. After you write the code for a problem, immediately verify that the code works by tracing through it with an example.Helps to flush out minor errors and bugs.
8. Make sure you check your code for all errors and special cases, especially boundary conditions. 
9. State the time and space complexity.

### When you get stuck:
Show interest in the problem and keep trying to solve it.
Note: Go back to an example. Try to move from the specific example to the general case and from there to the solution.
Try a different data structure.

 </details>

## Elements of the Programming Interview:
<details>
 <summary>Notes</summary>
 
 ### Introduction:
EPI aims to help engineers interviewing for software development positions. Primary focus on data structures (d.s.), algorithms (algors), system design (s.d.), and problem solving. 
Don’t waste precious time on topics you do not need to know. Dijkstra’s and other related algorithms should not be of importance. Master array, linked lists and string problems. Then, trees and graphs. 
### Chapter 1: 
### Getting Ready:
Before everything else, getting ready is the secret of success. -H. Ford.
Strategies For a Great Interview
The essence of strategy is choosing what not to do
### Approaching the Problem:
Clarify the question: A good way of clarifying the question is to state a concrete instance of the problem. For example, if the question is “find the first occurrence of a number greater than k in a sorted array”, you could ask “if the input array is <2,20,30> and k is 3, then are you supposed to return 1, the index of 20?” These questions can be formalized as unit tests.
Ask interviewer what time and space complexity s/he would like in your solution.
Work on concrete examples:
Spell out the brute force solution:
### Think out loud:
Apply patterns from past problem:
Focus on the top-level algorithms: Specify you will handle the main algorithm first, then the corner cases. Add TODO comments for portions that you want to come back to.
### General Conversation:
The point of this conversation is to answer the following questions:
Can the candidate clearly communicate a complex idea?
Is the candidate passionate about his work?
Is there a potential interest match with some project?
The only failures and mistakes in life are the ones you do not learn from.
### Conducting An Interview:
If you know both yourself and your enemy, you can win numerous battles without jeopardy. - “The Art of War”, Sun Tzu, 515 B.C.	
### Problem Solving: 
It’s not that I’m so smart, it’s just that I stay with problems longer. - A. Einstein
Bear in mind developing problem solving skills is like learning to play a musical instrument--books and teachers can point you in the right direction, but only your hard work will take you there.
### 4.1 Data structure review:
1. d.s - is a way of storing and organizing related data items so that they can be manipulated efficiently. 
2. Binary trees: used to represent hierarchical relationships.
3. Hash Tables: a d.s. Used to store keys, optionally, with corresponding values. Inserts, deletes, and lookups run O(1) time on average. One caveat is that these functions require good hash function--a mapping from the set of all possible keys to the integers which is similar to a uniform random assignment. Another caveat is that if the number of keys that is to be stored is not known in advance then the hash table needs to be periodically resized, which depending on how the resizing is implemented, can lead to some updates having O(n) complexity. 

 </details>
