# <p align="center">RoadMap for Computer Science</p>

# <p align="center">Preface</p>

# <p align="center">Contents</p>
- [Preface](#preface)
- [Community](#community)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Programming](#programming)
  - [Computer Architecture](#computer-architecture)
  - [Algorithms and Data Structures](#algorithms-and-data-structures)
  - [Math for CS](#math-for-cs)
  - [Operating Systems](#operating-systems)
  - [Computer Networking](#computer-networking)
  - [Databases](#databases)
  - [Languages and Compilers](#languages-and-compilers)
  - [Distributed Systems](#distributed-systems)

- [Additional Resources](#additional-resources)
- [OpenSource Projects](#open-source-projects)

## <p align="center">Community</p>

- You can also interact through [GitHub issues](https://github.com/fcc-hyd/issues).
- We also have a chat room! [Join the chat at [Discord](https://discordapp.com/channels/331374249921216514/334415199673122816)]

> **PS**: A forum is an ideal way to interact with other students as we do not lose important discussions, which usually occur in communication via chat apps.
**Please use our discord group for important discussions**.


# <p align="center">Curriculum</p>

**Curriculum version**: `1.0.0` (see [CHANGELOG](https://gist.github.com/pbteja1998/6e26c16ecc2eb9291cfea2447f0b9956/revisions))

- [Prerequisites](#prerequisites)
- [Programming](#programming)
- [Computer Architecture](#computer-architecture)
    - [Getting Started](#computer-architecture)
    - [Boolean Logic](#computer-architecture)
    - [Boolean Arithmetic](#computer-architecture)
    - [Sequential Logic](#computer-architecture)
    - [Machine Language](#computer-architecture)
    - [Computer Architecture](#computer-architecture)
    - [Assembler](#computer-architecture)
    - [VM I: Stack Arithmetic](#computer-architecture)
    - [VM II: Program Control](#computer-architecture)
    - [High-Level Language](#computer-architecture)
    - [Compiler I: Syntax Analysis](#computer-architecture)
    - [Compiler II: Code Generation](#computer-architecture)
    - [Operating System](#computer-architecture)
    - [MIPS Architecture](#mips-architecture)
    - [Additional Resources](#additional-resources)
- [Algorithms and Data Structures](#algorithms-and-data-structures)
    - [Data Structutes](#data-structures)
        - [Basic Data Structures](#basic-data-structures)
            - [Array](#array)
            - [Matrix](#matrix)
            - [Linked List](#linkedlists-stacks-and-queues)
            - [Stack](#linkedlists-stacks-and-queues)
            - [Queue](#linkedlists-stacks-and-queues)
            - [Binary Tree](#tree-based-data-structures)
            - [Binary Search Tree](#tree-based-data-structures)
            - [Heap](#tree-based-data-structures)
            - [Hashing](#hashing)
            - [Graph](#graph)
        - [Advanced Data Structures](#advanced-data-structures)
            - [Advanced Lists](#advanced-data-structures)
            - [Segment Trees](#advanced-data-structures)
            - [Trie](#advanced-data-structures)
            - [Binary Indexed Tree](#advanced-data-structures)
            - [Suffix Array and Suffix Tree](#advanced-data-structures)
            - [AVL Tree](#advanced-data-structures)
            - [Splay Tree](#advanced-data-structures)
            - [B Tree](#advanced-data-structures)
            - [Red-Black Tree](#advanced-data-structures)
            - [K Dimensional Tree](#advanced-data-structures)
    - [Algorithms](#algorithms)
        - [Analysis](#analysis)
        - [Searching and Sorting](#searching-and-sorting)
        - [Greedy Algorithms](#greedy-algorithms)
        - [Dynamic Programming](#dynamic-programming)
        - [Pattern Searching](#pattern-searching)
        - [String Algorithms](#string-algorithms)
        - [Backtracking](#backtracking)
        - [Divide and Conquer](#divide-and-conquer)
        - [Geometric Algorithms](#geometric-algorithms)
        - [Mathematical Algorithms](#mathematical-algorithms)
        - [Bit Alogorithms](#bit-algorithms)
        - [Graph Algorithms](#graph-algorithms)
        - [Randomized Algorithms](#randomized-algorithms)
        - [Branch and Bound](#branch-and-bound)
        - [Misc](#misc)
- [Math for CS](#math-for-cs)
- [Operating Systems](#operating-systems)
    - [Overview](#overview) 
        - [Introduction](#introduction)
        - [Operating System Structures](#operating-system-structures)
    - [Process Management](#process-management)
        - [Processes](#processes)
        - [Threads](#threads)
        - [CPU Scheduling](#cpu-scheduling)
        - [Process Synchronization](#process-synchronization)
        - [Deadlocks](#deadlocks)
    - [Memory Management](#memory-management)
        - [Main Memory](#main-memory)
        - [Virtual Memory](#virtual-memory)
    - [Storage Management](#storage-management)
        - [Mass-Storage Structure](#mass-storage-structure)
        - [File-System Interface](#file-system-interface)
        - [File-System Implemenatation](#file-system-implementation)
        - [I/O Systems](#i/o-systems)
    - [Protection and Security](#protection-and-security)
        - [Protection](#protection)
        - [Security](#security)
- [Computer Networking](#computer-networking)
    - [Computer Networks and the Internet](#computer-networks-and-the-internet)
    - [Application Layer](#application-layer)
    - [Transport Layer](#transport-layer)
    - [Network Layer](#network-layer)
    - [Link Layer](#link-layer)
    - [Wireless and Mobile Networks](#wireless-and-mobile-networks)
    - [Multimedia Networking](#multimedia-networking)
    - [Security in Computer Networks](#security-in-computer-networks)
    - [Network Management](#network-management)
- [Databases](#databases)
- [Languages and Compilers](#languages-and-compilers)
- [Distributed Systems](#distributed-systems)
- [Final project](#final-project)


## <p align="center">Prerequisites</p>

- This course assumes the student has no prerequisites.

## <p align="center">Computer Architecture</p>
We are going to follow [Nand2Tetris](http://www.nand2tetris.org/course.php) course and its corresponding [Coursera](https://www.coursera.org/learn/build-a-computer/home/welcome) Videos for this section

Concept | Video Resource | Text Resource | Lecture | Task
:-- | :--: | :--: | :--: | :--:
Getting Started | [Week 1](https://www.coursera.org/learn/build-a-computer/home/week/1) | | | [Task 0](http://www.nand2tetris.org/00.php)
Boolean Logic | [Week 2](https://www.coursera.org/learn/build-a-computer/home/week/2) | [Chapter 1](http://www.nand2tetris.org/chapters/chapter%2001.pdf) | [Lecture 1](http://www.nand2tetris.org/lectures/PDF/lecture%2001%20Boolean%20logic.pdf) | [Task 1](http://www.nand2tetris.org/01.php)
Boolean Arithmetic | [Week 2](https://www.coursera.org/learn/build-a-computer/home/week/2) | [Chapter 2](http://www.nand2tetris.org/chapters/chapter%2002.pdf) | [Lecture 2](http://www.nand2tetris.org/lectures/PDF/lecture%2002%20Boolean%20arithmetic.pdf) | [Task 2](http://www.nand2tetris.org/02.php)
Sequential Logic | [Week 3](https://www.coursera.org/learn/build-a-computer/home/week/3) | [Chapter 3](http://www.nand2tetris.org/chapters/chapter%2003.pdf) | [Lecture 3](http://www.nand2tetris.org/lectures/PDF/lecture%2003%20sequential%20logic.pdf) | [Task 3](http://www.nand2tetris.org/03.php)
Machine Language | [Week 4](https://www.coursera.org/learn/build-a-computer/home/week/4) | [Chapter 4](http://www.nand2tetris.org/chapters/chapter%2004.pdf) | [Lecture 4](http://www.nand2tetris.org/lectures/PDF/lecture%2004%20machine%20language.pdf) | [Task 4](http://www.nand2tetris.org/04.php)
Computer Architecture | [Week 5](https://www.coursera.org/learn/build-a-computer/home/week5) | [Chapter 5](http://www.nand2tetris.org/chapters/chapter%2005.pdf) | [Lecture 5](http://www.nand2tetris.org/lectures/PDF/lecture%2005%20computer%20architecture.pdf) | [Task 5](http://www.nand2tetris.org/05.php)
Assembler | [Week 6](https://www.coursera.org/learn/build-a-computer/home/week/6) | [Chapter 6](http://www.nand2tetris.org/chapters/chapter%2006.pdf) | [Lecture 6](http://www.nand2tetris.org/lectures/PDF/lecture%2006%20assembler.pdf) | [Task 6](http://www.nand2tetris.org/06.php)
VM I: Stack Arithmetic | [Week 7](https://www.coursera.org/learn/nand2tetris2/home/week/1) | Chapter 7 | [Lecture 7](http://www.nand2tetris.org/lectures/PDF/lecture%2007%20virtual%20machine%20I.pdf) | [Task 7](http://www.nand2tetris.org/07.php)
VM II: Program Control | [Week 8](https://www.coursera.org/learn/nand2tetris2/home/week/2) | Chapter 8 | [Lecture 8](http://www.nand2tetris.org/lectures/PDF/lecture%2008%20virtual%20machine%20II.pdf) | [Task 8](http://www.nand2tetris.org/08.php)
High-Level Language | [Week 9](https://www.coursera.org/learn/nand2tetris2/home/week/3) | Chapter 9 | [Lecture 9](http://www.nand2tetris.org/lectures/PDF/lecture%2009%20high%20level%20language.pdf) | [Task 9](http://www.nand2tetris.org/09.php)
Compiler I: Syntax Analysis | [Week 10](https://www.coursera.org/learn/nand2tetris2/home/week/4) | Chapter 10 | [Lecture 10](http://www.nand2tetris.org/lectures/PDF/lecture%2010%20compiler%20I.pdf) | [Task 10](http://www.nand2tetris.org/10.php)
Compiler II: Code Generation | [Week 11](https://www.coursera.org/learn/nand2tetris2/home/week/5) | Chapter 11 | [Lecture 11](http://www.nand2tetris.org/lectures/PDF/lecture%2011%20compiler%20II.pdf) | [Task 11](http://www.nand2tetris.org/11.php)
Operating System | [Week 12](https://www.coursera.org/learn/nand2tetris2/home/week/6) | Chapter 12 | [Lecture 12](http://www.nand2tetris.org/lectures/PDF/lecture%2012%20OS.pdf) | [Task 12](http://www.nand2tetris.org/12.php)

### MIPS Architecture:
- [MIPS Quick Tutorial](https://drive.google.com/open?id=0BzVkvO2npwwRbG80dHJKT1JaZ1U)
- [MIPS Instruction Reference](https://drive.google.com/open?id=0BzVkvO2npwwRZ3duM0JYR1ZZb2M)
- [MIPS Instruction Formats](https://drive.google.com/open?id=0BzVkvO2npwwRVkZXeTV4VVk4cVU)
- [Subroutines in MIPS](https://drive.google.com/open?id=0BzVkvO2npwwRUWpGb1FxYkpPMlU)
- [Rotines in MIPS](https://drive.google.com/open?id=0BzVkvO2npwwRMDd2VWVMTVh2NU0)
- [MIPS Arrays](https://drive.google.com/open?id=0BzVkvO2npwwRekNPNlRzcXdJUnM)
- [MIPS Code Simulator](http://rivoire.cs.sonoma.edu/cs351/wemips/)
- [SPIM MIPS Simulator](http://spimsimulator.sourceforge.net/)

### Additional Resources:
- [Computer Organisation and Design](https://drive.google.com/open?id=0BzVkvO2npwwRSFhxU0llVkVPZkE)  5th Edition (2014) by DAVID A PATTERSON AND JOHN HENNESSY
- [Structured Computer Organization](https://drive.google.com/open?id=0BzVkvO2npwwRaHZXcnJLZUthRjQ) 6th Edition (2013) by ANDREW S. TANENBAUM & TODD AUSTIN
- [Computer Organization and Architecture](https://drive.google.com/open?id=0BzVkvO2npwwRT2M1Rnkyc0g0b2s) 9th Edition (2013) by WILLLIAM-STALLINGS
- [Computer organisation](https://drive.google.com/open?id=0BzVkvO2npwwRMmdfSlFBdmVmRGM) 5th Edition (2002) by CARL HAMACHER, Z.VRANESIC and S.ZAKY (MGH Publications)
- [Computer System Architecture](https://drive.google.com/open?id=0BzVkvO2npwwRVlRjdncyc2NaZzA) 3rd Edition (2004) by MORRIS MANO

## <p align="center">Algorithms and Data Structures</p>

## Basic Data Structures

### LinkedLists Stacks and Queues:

Concept | Text Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--:
Linked List | [Geeks for Geeks](http://www.geeksforgeeks.org/linked-list-set-1-introduction/) | [Geeks for Geeks](https://www.youtube.com/watch?v=ge8iG7JecR4) | | [Problems](#linked-list)
Stack | [Array Implementation](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/) | | [Using Array](https://www.cs.usfca.edu/~galles/visualization/StackArray.html) | [Problems](#stack)
Stack | [Linked List Implementation](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/) | | [Using Linked List](https://www.cs.usfca.edu/~galles/visualization/StackLL.html) | [Problems](#stack)
Queue | [Array Implementation](http://www.geeksforgeeks.org/queue-set-1introduction-and-array-implementation/) | | [Using Array](https://www.cs.usfca.edu/~galles/visualization/QueueArray.html) | [Problems](#queue)
Queue | [Linked List Implementation](http://geeksquiz.com/queue-set-2-linked-list-implementation/) | | [Using Linked List](https://www.cs.usfca.edu/~galles/visualization/QueueLL.html) | [Problems](#queue)
[Dequeue](http://www.geeksforgeeks.org/deque-set-1-introduction-applications/) | [Circular Array Implementation](http://www.geeksforgeeks.org/implementation-deque-using-circular-array/) | | | [Problems](#queue-1)
Priority Queue | [Geeks for Geeks](http://www.geeksforgeeks.org/priority-queue-set-1-introduction/) | | | [Problems](#queue)

#### Tasks:
##### Linked List:
- Create a singly Linked List and implement the following functions
    -  [Insert a node](http://www.geeksforgeeks.org/linked-list-set-2-inserting-a-node/)
        - Insert at the head
        - Insert at the tail
        - Insert in the middle
    -  [Delete a node](http://www.geeksforgeeks.org/linked-list-set-3-deleting-node/)
    -  Search for a node
    -  [Swap](http://www.geeksforgeeks.org/swap-nodes-in-a-linked-list-without-swapping-data/) two nodes without swapping data
    -  Reverse a Linked List
-  Create a doubly Linked List and implement the following functions
    -  Insert a node
        - Insert at the head
        - Insert at the tail
        - Insert in the middle
    -  Delete a node
    -  Search for a node
    -  Swap two nodes
    -  [Reverse](http://www.geeksforgeeks.org/reverse-a-linked-list/) a Linked List
-  Create a circular Linked List and implement the following functions
    -  Insert a node
    -  Delete a node
    -  Search for a node
    -  Swap two nodes
- [Some other problems](http://www.geeksforgeeks.org/data-structures/linked-list/)

##### Stack:
- Check for [balanced parentheses](http://www.geeksforgeeks.org/?p=6547) in an expression using [Stack](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/)
- Solve [Iterative Tower of Hanoi](http://www.geeksforgeeks.org/iterative-tower-of-hanoi/) problem using [Stack](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/)
- Solve [Stock Span](http://www.geeksforgeeks.org/the-stock-span-problem/) problem using [Stack](http://www.geeksforgeeks.org/stack-data-structure-introduction-program/)
- [Some other problems](http://www.geeksforgeeks.org/stack-data-structure/)
 
##### Queue:
- [Implement Queue using Stacks](http://www.geeksforgeeks.org/?p=5009)
- [Implement Stack using Single Queue](http://www.geeksforgeeks.org/implement-a-stack-using-single-queue/)
- Implement Dequeue using doubly Linked List
- [Some other problems](http://www.geeksforgeeks.org/queue-data-structure/)


### Tree Based Data Structures:
Concept | Text Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--:
Binary Tree | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-tree-set-1-introduction/) | | | [Problems](#binary-tree)
Binary Tree Properties | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-tree-set-2-properties/) | | | 
Binary Tree Types | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-tree-set-3-types-of-binary-tree/) | | | 
Hand Shaking Lemma | [Geeks for Geeks](http://www.geeksforgeeks.org/handshaking-lemma-and-interesting-tree-properties/) | | |
BFS vs DFS | [Geeks for Geeks](http://www.geeksforgeeks.org/bfs-vs-dfs-binary-tree/) | | [BFS](https://www.cs.usfca.edu/~galles/visualization/BFS.html) [DFS](https://www.cs.usfca.edu/~galles/visualization/DFS.html) |
Binary Search Tree | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/) | | [Visualization](https://www.cs.usfca.edu/~galles/visualization/BST.html) | [Problems](#binary-search-tree)
Heap | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-heap/) | [Geeks for Geeks](https://www.youtube.com/watch?v=uZj0hetLFHU) |  [Visualization](https://www.cs.usfca.edu/~galles/visualization/Heap.html) | [Problems](#heap) [1](https://www.codechef.com/problems/REVERSE)
Binomial Heap | [Geeks for Geeks](http://www.geeksforgeeks.org/binomial-heap-2/) | [Geeks for Geeks](https://www.youtube.com/watch?v=e_gh1aD4v-A) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/BinomialQueue.html) |
Fibonacci Heap | [Geeks for Geeks](http://www.geeksforgeeks.org/fibonacci-heap-set-1-introduction/) | | [Visualization](https://www.cs.usfca.edu/~galles/visualization/FibonacciHeap.html) |
Heap Sort | [Geeks for Geeks](http://www.geeksforgeeks.org/heap-sort/) | [Geeks for Geeks](https://www.youtube.com/watch?v=MtQL_ll5KhQ) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/HeapSort.html)

#### Tasks:
##### Binary Tree:
- Traversals:
    - [Inorder Traversal](http://www.geeksforgeeks.org/inorder-tree-traversal-without-recursion/) without recursion
    - [Inorder Traversal](http://www.geeksforgeeks.org/inorder-tree-traversal-without-recursion-and-without-stack/) without recursion and without stack
    - [Iterative PreOrder Traversal](http://www.geeksforgeeks.org/iterative-preorder-traversal/)
    - [Preorder Traversal](http://www.geeksforgeeks.org/morris-traversal-for-preorder/) without recursion and without stack
    - [Iterative Post Order Traversal](http://www.geeksforgeeks.org/iterative-postorder-traversal/) using two stacks
    - [Iterative Post Order Traversal](http://www.geeksforgeeks.org/iterative-postorder-traversal-using-stack/) using only one stack
    - Print [Post Order Traversal from Inorder and Preorder Traversals](http://www.geeksforgeeks.org/print-postorder-from-given-inorder-and-preorder-traversals/)
- Construct
    - [Tree using Inorder and Preorder Traversals](http://www.geeksforgeeks.org/construct-tree-from-given-inorder-and-preorder-traversal/)
    - [Binary Tree from Post Order and Inorder Traversals](http://www.geeksforgeeks.org/construct-a-binary-tree-from-postorder-and-inorder/)
    - [Full Binary tree from Preorder and Post Order Traversals](http://www.geeksforgeeks.org/full-and-complete-binary-tree-from-given-preorder-and-postorder-traversals/)
- [Some Other Problems](http://www.geeksforgeeks.org/binary-tree-data-structure/)

##### Binary Search Trees:
- [Search and insert a node](http://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/)
- [Delete a node](http://www.geeksforgeeks.org/binary-search-tree-set-2-delete/)
- [Check if a given Binary tree is a BST](http://www.geeksforgeeks.org/a-program-to-check-if-a-binary-tree-is-bst-or-not/)
- [Convert given binary tree to a BST](http://www.geeksforgeeks.org/binary-tree-to-binary-search-tree-conversion/)
- [Lowest Common Ancestor](http://www.geeksforgeeks.org/lowest-common-ancestor-in-a-binary-search-tree/) of a BST
- Print [Sorted order of all the nodes of a BST](http://www.geeksforgeeks.org/sorted-order-printing-of-an-array-that-represents-a-bst/)
- [Kth Smallest Element](http://www.geeksforgeeks.org/kth-smallest-element-in-bst-using-o1-extra-space/) in BST using O(1) extra space
- [Some Other Problems](http://www.geeksforgeeks.org/binary-search-tree-data-structure/)

##### Heap:
- [Implement Min Heap](http://www.geeksforgeeks.org/binary-heap/)
    - Insertion
    - Deletion
    - Get Minimum Node
    - Decrease the value of node
    - Remove Minimum Node
- [Check if a given binary tree is a heap](http://www.geeksforgeeks.org/check-if-a-given-binary-tree-is-heap/)
- [Heap Sort](http://www.geeksforgeeks.org/heap-sort/)
- [Some Other Problems](http://www.geeksforgeeks.org/heap-data-structure/)

### Hashing:
Concept | Text Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--:
Hashing | [Introduction](http://www.geeksforgeeks.org/hashing-set-1-introduction/) | [Geeks for Geeks](https://www.youtube.com/watch?v=wWgIAphfn2U) | |
Separare Chaining | [Geeks for Geeks](http://www.geeksforgeeks.org/hashing-set-2-separate-chaining/) | [Geeks for Geeks](https://www.youtube.com/watch?v=_xA8UvfOGgU) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/OpenHash.html) |
Open Addressing | [Geeks for Geeks](http://www.geeksforgeeks.org/hashing-set-3-open-addressing/) | [Geeks for Geeks](https://www.youtube.com/watch?v=Dk57JonwKNk) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/ClosedHash.html) |
Cuckoo Hashing | [Geeks for Geeks](http://www.geeksforgeeks.org/cuckoo-hashing/) | | |
String Hashing | [Threads@IIIT-H](https://threads-iiith.quora.com/String-Hashing-for-competitive-programming) | | |
BST vs Hash Tables | [Geeks for Geeks](http://www.geeksforgeeks.org/advantages-of-bst-over-hash-table/) | | |

#### Tasks:
- [Design a data structure that supports insert, delete, search and getRandom in constant time](http://www.geeksforgeeks.org/design-a-data-structure-that-supports-insert-delete-search-and-getrandom-in-constant-time/)
- Check if a given string is a Palindrome using String Hashing
- [Check if a given substring of a string is Palindrome](http://www.geeksforgeeks.org/palindrome-substring-queries/)
- [Largest Subarray with equal number of O's and 1's](http://www.geeksforgeeks.org/largest-subarray-with-equal-number-of-0s-and-1s/) in O(n) Time Complexity
- [Longest Consecutive Subsequence](http://www.geeksforgeeks.org/longest-consecutive-subsequence/) in O(n) Time Complexity
- [Some Other Problems](http://www.geeksforgeeks.org/hashing-data-structure/)

### Graph:
Concept | Text Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--:
Graph and its Representation | [Adjacency Matrix and Adjacency List](http://www.geeksforgeeks.org/graph-and-its-representations/) | [Geeks for Geeks](https://www.youtube.com/watch?v=1n5XPFcvxds) | | 
Breadth First Search | [Geeks for Geeks](http://www.geeksforgeeks.org/breadth-first-traversal-for-a-graph/) | [Geeks for Geeks](https://www.youtube.com/watch?v=0u78hx-66Xk) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/BFS.html) | Implement BFS
Depth First Search | [Geeks for Geeks](http://www.geeksforgeeks.org/depth-first-traversal-for-a-graph/) | [Geeks for Geeks](https://www.youtube.com/watch?v=Y40bRyPQQr0) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/DFS.html) | Implement DFS
Cycle Detection in Directed Graph | [Geeks for Geeks](http://www.geeksforgeeks.org/detect-cycle-in-a-graph/) | [Geeks for Geeks](https://www.youtube.com/watch?v=joqmqvHC_Bo) | | 
Cycle Detection in UnDirected Graph | [Disjoint Set or Union Find](http://www.geeksforgeeks.org/union-find/) | [Geeks for Geeks](https://www.youtube.com/watch?v=mHz-mx-8lJ8) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/DisjointSets.html) | 
Cycle Detection in UnDirected Graph | [Using DFS](http://www.geeksforgeeks.org/detect-cycle-undirected-graph/) | [Geeks for Geeks](https://www.youtube.com/watch?v=6ZRhq2oFCuo) | | 
Topological Sorting | [Using DFS](http://www.geeksforgeeks.org/topological-sorting/) | [Geeks for Geeks](https://www.youtube.com/watch?v=Q9PIxaNGnig) | [Using DFS](https://www.cs.usfca.edu/~galles/visualization/TopoSortDFS.html) |
Topological Sorting | [Using Indegree](http://www.geeksforgeeks.org/topological-sorting-indegree-based-solution/) |  | [Using Indegree](https://www.cs.usfca.edu/~galles/visualization/TopoSortIndegree.html) |


#### Tasks:
- Implement
    - [DFS](http://www.geeksforgeeks.org/depth-first-traversal-for-a-graph/)
    - [BFS](http://www.geeksforgeeks.org/breadth-first-traversal-for-a-graph/)
    - [Iterative Depth First Search(IDS)](http://www.geeksforgeeks.org/iterative-depth-first-traversal/)
    - [Iterative Deepening Search(IDS) or Iterative Deepening Depth First Search(IDDFS)](http://www.geeksforgeeks.org/iterative-deepening-searchids-iterative-deepening-depth-first-searchiddfs/)
- Detect Cycle in a Directed Graph
    - [Using DFS](http://www.geeksforgeeks.org/detect-cycle-in-a-graph/)
    - [Using Colors](http://www.geeksforgeeks.org/detect-cycle-direct-graph-using-colors/)
- Detect Cycle in an Undirected Graph
    - [Using DFS](http://www.geeksforgeeks.org/detect-cycle-undirected-graph/)
    - [Using Union Find Algorithm](http://www.geeksforgeeks.org/union-find/)
- [Topological Sorting](http://www.geeksforgeeks.org/topological-sorting-indegree-based-solution/) using Indegree
- [Some Other Problems](http://www.geeksforgeeks.org/graph-data-structure-and-algorithms/)

## Advanced Data Structures:
Concept | TopCoder | Geeks for Geeks  | Other Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--: | :--: | :--:
Trie | [Using Tries](https://www.topcoder.com/community/data-science/data-science-tutorials/using-tries/) | [Insert and Search](http://www.geeksforgeeks.org/trie-insert-and-search/) [Delete](http://www.geeksforgeeks.org/trie-delete/) | [Threads@IIITH](https://threads-iiith.quora.com/Tutorial-on-Trie-and-example-problems) | [Geeks for Geeks](https://www.youtube.com/watch?v=dUBkaqrcYT8) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/Trie.html) | [1](http://www.spoj.com/problems/SUBXOR/) [2](https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&Itemid=8&category=345&page=show_problem&problem=2683) [3](http://www.codechef.com/problems/EST)
Suffix Array | [Top Coder](https://apps.topcoder.com/forums/;jsessionid=BC99925E58CB2628CA9AA3AFC13F6593?module=Thread&threadID=627379&start=0) | [Introduction](http://www.geeksforgeeks.org/suffix-array-set-1-introduction/) | [Code Chef](https://discuss.codechef.com/questions/21385/a-tutorial-on-suffix-arrays) [Stanford](http://web.stanford.edu/class/cs97si/suffix-array.pdf) | [Geeks for Geeks](https://www.youtube.com/watch?v=uxA__b23t2w) | | [1](http://www.spoj.com/problems/SUBST1/) [2](http://www.codechef.com/problems/MOU1H) |
Depth First Search | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/introduction-to-graphs-and-their-data-structures-section-2/#depth) | [Geeks for Geeks](http://www.geeksforgeeks.org/depth-first-traversal-for-a-graph/) | | [Geeks for Geeks](https://www.youtube.com/watch?v=Y40bRyPQQr0) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/DFS.html) | [1](http://www.spoj.com/problems/PARADOX/) [2](http://www.spoj.com/problems/BUGLIFE/) [3](http://www.spoj.com/problems/PT07Z/)
Breadth First Search | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/introduction-to-graphs-and-their-data-structures-section-2/#breadth) | [Geeks for Geeks](http://www.geeksforgeeks.org/breadth-first-traversal-for-a-graph/) | | [Geeks for Geeks](https://www.youtube.com/watch?v=0u78hx-66Xk) | [Visualization](https://www.cs.usfca.edu/~galles/visualization/BFS.html) | [1](https://www.codechef.com/problems/DIGJUMP) [2](http://www.spoj.com/problems/ONEZERO/) [3](http://www.spoj.com/problems/NAKANJ/) [Flood Fill](https://www.topcoder.com/community/data-science/data-science-tutorials/how-to-find-a-solution/#floodfill)
Binary Indexed Tree | [Top Coder](http://www.spoj.com/problems/SHPATH/) | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-indexed-tree-or-fenwick-tree-2/) | [CodeForces](http://codeforces.com/blog/entry/619) [OriginalPaper](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=AB3AEBC0736E52FA815A3D4C633DE52F?doi=10.1.1.14.8917&rep=rep1&type=pdf) [Other](https://sanugupta.wordpress.com/2014/08/29/binary-indexed-tree-fenwick-tree/) [Stack Exchange](https://cs.stackexchange.com/questions/10538/bit-what-is-the-intuition-behind-a-binary-indexed-tree-and-how-was-it-thought-a/10541#10541) | | | [1](http://www.spoj.com/problems/HORRIBLE/) [2](http://www.spoj.com/problems/YODANESS/) [3](http://www.spoj.com/problems/INVCNT/) [4](http://www.spoj.com/problems/NICEDAY/) [5](http://www.spoj.com/problems/CTRICK/) [6](http://www.spoj.com/problems/DQUERY/) [7](http://www.spoj.com/problems/MCHAOS/)
Segment Tree(with Lazy Propogation) | [RangeMinimumQuery,  LowestCommonAncestor](https://www.topcoder.com/community/data-science/data-science-tutorials/range-minimum-query-and-lowest-common-ancestor/) | [Geeks for Geeks](http://www.geeksforgeeks.org/segment-tree-set-1-sum-of-given-range/) | [1](http://se7so.blogspot.in/2012/12/segment-trees-and-lazy-propagation.html) [2](http://letuskode.blogspot.in/2013/01/segtrees.html) [3](http://e-maxx.ru/algo/segment_tree) [Code Chef](https://discuss.codechef.com/questions/38770/lazy-propagation) | | | [1](http://www.spoj.com/problems/HORRIBLE/) [2](https://www.codechef.com/problems/IDOLS)
Sparse Table | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/range-minimum-query-and-lowest-common-ancestor/) | | [C++](https://mayanknatani.wordpress.com/2013/07/15/range-minimum-query/) [Java](https://sites.google.com/site/indy256/algo/sparse_table_rmq) [Hacker Earth](https://www.hackerearth.com/practice/notes/sparse-table/) 

Concept | Text Resource | Video Resource | Visualization | Tasks
:-- | :--: | :--: | :--: | :--:
Suffix Tree | [Introduction](http://www.geeksforgeeks.org/pattern-searching-set-8-suffix-tree-introduction/) | [Geeks for Geeks](https://www.youtube.com/watch?v=N70NPX6xgsA) | |
AVL Tree | [Insertion](http://www.geeksforgeeks.org/avl-tree-set-1-insertion/) | [Insertion](https://www.youtube.com/watch?v=ygZMI2YIcvk), [Deletion](http://www.geeksforgeeks.org/avl-tree-set-2-deletion/),  [Handling Duplicate Keys](http://www.geeksforgeeks.org/avl-with-duplicate-keys/)| [Visualization](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html)
B Tree | [Geeks for Geeks](http://www.geeksforgeeks.org/b-tree-set-1-introduction-2/) | | [Visualization](https://www.cs.usfca.edu/~galles/visualization/BTree.html) |
Other Advances Data Structures and related problems  | [Geeks for Geeks](http://www.geeksforgeeks.org/advanced-data-structures/) | | |


### Tasks:
#### Trie:
- [Longest Common Prefix](http://www.geeksforgeeks.org/longest-common-prefix-set-5-using-trie/)
- [Pallindrome Pair in an array of words](http://www.geeksforgeeks.org/palindrome-pair-in-an-array-of-words-or-strings/) in less than O(n^2)
#### Binary Indexed Tree:
- We have an array arr[0 . . . n-1]. Design a Data Structure that does the following two operations in `O(logn)` time.
    - Find the sum of first i elements.
    - Change value of a specified element of the array arr[i] = x where 0 <= i <= n-1.
#### AVL Tree:
- [Insertion](http://www.geeksforgeeks.org/avl-tree-set-1-insertion/)
- [Deletion](http://www.geeksforgeeks.org/avl-tree-set-2-deletion/)
- [Handling Duplicate Keys](http://www.geeksforgeeks.org/avl-with-duplicate-keys/)
#### B Tree:
- [Insertion](http://www.geeksforgeeks.org/b-tree-set-1-insert-2/)
- [Deletion](http://www.geeksforgeeks.org/b-tree-set-3delete/)

## Algorithms
Algorithm | Top Coder | Video Resource | Geeks for Geeks | Other Resource | Task(s)
:-- | :--: | :--: | :--: | :--: | :--:
Binary Search | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/binary-search/) |  | [Geeks for Geeks](http://www.geeksforgeeks.org/binary-search/) | | [Problem](http://www.spoj.com/problems/AGGRCOW/)
Quick Sort | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/sorting/) |  | [Geeks for Geeks](http://www.geeksforgeeks.org/quick-sort/) | 
Merge Sort | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/sorting/) | | [Geeks for Geeks](http://www.geeksforgeeks.org/merge-sort/) | 
Rabin-Karp and Knuth-Morris-Pratt Algorithms | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/introduction-to-string-searching-algorithms/) | | [Geeks for Geeks](http://www.geeksforgeeks.org/searching-for-patterns-set-2-kmp-algorithm/) | [Tutorial](http://keithschwarz.com/interesting/code/?dir=knuth-morris-pratt) | [1](https://www.codechef.com/problems/SSTORY) [2](http://codeforces.com/problemset/problem/271/D)
Dijkstra's Algorithm | [Heap Implementation](https://www.topcoder.com/community/data-science/data-science-tutorials/introduction-to-graphs-and-their-data-structures-section-3/#dijkstra) | | | [Greedy](http://e-maxx.ru/algo/dijkstra) [Heap](http://e-maxx.ru/algo/dijkstra_sparse) [Other Resource](http://zobayer.blogspot.in/2009/12/dijkstras-algorithm-in-c.html) | [1](https://www.codechef.com/problems/REN2013G) [2](http://www.spoj.com/problems/EZDIJKST/) [3](http://www.spoj.com/problems/SHPATH/)
Z Algorithm | | | | [Code Forces](http://codeforces.com/blog/entry/3107) [Other](https://www.cs.umd.edu/class/fall2011/cmsc858s/Lec02-zalg.pdf) | 
Floyd-Warshall Algorithm | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/introduction-to-graphs-and-their-data-structures-section-3/#floydWarshall) | | [Geeks for Geeks](http://www.geeksforgeeks.org/dynamic-programming-set-16-floyd-warshall-algorithm/) | | [1](http://www.spoj.com/problems/AMR11F/) [2](https://community.topcoder.com/stat?c=problem_statement&pm=2356)
Suffix Automaton | | | [1](http://www.geeksforgeeks.org/searching-for-patterns-set-5-finite-automata/) [2](http://www.geeksforgeeks.org/pattern-searching-set-5-efficient-constructtion-of-finite-automata/) | [Other](http://e-maxx.ru/algo/suffix_automata) | [1](https://www.codechef.com/problems/SUBQUERY) [2](https://www.codechef.com/problems/TSUBSTR) [3](https://www.codechef.com/problems/SSTORY) [4](https://www.codechef.com/problems/MOU1H)
LCA | [Top Coder](https://www.topcoder.com/community/data-science/data-science-tutorials/range-minimum-query-and-lowest-common-ancestor/) | | | [1](http://wwwmayr.in.tum.de/konferenzen/Jass08/courses/1/moufatich/El_Moufatich_Paper.pdf) | [1](https://www.codechef.com/LTIME14/problems/TALCA) [2](http://www.spoj.com/problems/LCA/) [3](https://www.codechef.com/problems/TRIPS) 
Extended Euclid's Algorithm | | | | [Code Chef](https://discuss.codechef.com/questions/20842/a-tutorial-on-the-extended-euclids-algorithm) |



## <p align="center">Operating Systems</p>

We are going to follow **Operating System Concepts, 7th Edition by Silberschatz, Galvin, Gagne** [book]() and the corresponding [Lecture Slides](http://bcs.wiley.com/he-bcs/Books?action=resource&bcsId=2217&itemId=0471694665&resourceId=5004) and [Practice Exercises](http://bcs.wiley.com/he-bcs/Books?action=resource&bcsId=2217&itemId=0471694665&resourceId=5097).

This course assumes that you already know basic programming in C/C++. Some of the projects that will be given in this course requires C Programming and running on a Linux Operating System.

### Overview:
#### Preface from the Book:
<p>
Chapters 1 and 2 explain what operating systems are, what they do, and how they are designed and constructed. They discuss what the common features of an operating system are, what an operating system does for the user, and what it does for the computer-system operator. The presentation is motivational and explanatory in nature. We have avoided a discussion of how things are done internally in these chapters. Therefore, they are suitable for individual readers or for students in lower-level classes who want to learn what an operating system is without getting into the details of the internal algorithms.
</p>

Chapter | Lecture Slides | Practice Exercises | Powerpoint Presentations | Source Code | Tasks
:-- | :--: | :--: | :--: | :--: | :--
[Introduction](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15703) | [Lecture 1 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15703) | [Execise 1 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15703) | [PPT 1 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15703) | [Souce Code 1 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15703)
[Operating-System Structures](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15704) | [Lecture 2 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15704) | [Execise 2 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15704) | [PPT 2 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15704) | [Souce Code 2 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15704)


#### Index:
- ###### Introduction
    - What Operating Systems Do
    - Computer-System Organization
    - Computer-System Architecture
    - Operating-System Structure
    - Operating-System Operations
    - Process Management
    - Memory Management
    - Storage Management
    - Protection and Security
    - Distributed Systems
    - Special-Purpose Systems
    - Computing Environments
- ###### Operating-System Structures
    - Operating-System Services
    - User and Operating-System Interface
    - System Calls
    - Types of System Calls
    - System Programs
    - Operating-System Design and Implementation
    - Operating-System Structure
    - Virtual Machines
    - Operating-System Generation
    - System Boot

#### Tasks:
- [Reverse the contents of the given file using System calls](https://gist.github.com/pbteja1998/3884f173b2157ba20e72283a070c87e1)

### Process Management:
#### Preface from the Book:
<p>
Chapters 3 through 7 describe the process concept and concurrency as the heart of modern operating systems. A process is the unit of work in a system. Such a system consists of a collection of concurrently executing processes, some of which are operating-system processes (those that execute system code) and the rest of which are user processes (those that execute user code). These chapters cover methods for process scheduling, interprocess communication, process synchronization, and deadlock handling. Also included under this topic is a discussion of threads.
</p>

Chapter | Lecture Slides | Practice Exercises | Powerpoint Presentations | Source Code | Tasks
:-- | :--: | :--: | :--: | :--: | :--
[Processes](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15705) | [Lecture 3 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15705) | [Execise 3 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15705) | [PPT 3 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15705) | [Souce Code 3 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15705)
[Threads](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15706) | [Lecture 4 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15706) | [Execise 4 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15706) | [PPT 4 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15706) | [Souce Code 4 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15706)
[CPU Scheduling](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15707) | [Lecture 5 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15707) | [Execise 5 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15707) | [PPT 5 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15707) | [Souce Code 5 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15707)
[Process Synchronization](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15708) | [Lecture 6](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15708) | [Execise 6 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15708) | [PPT 6 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15708) | [Souce Code 6 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15708)
[Deadlocks](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15709) | [Lecture 7 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15709) | [Execise 7 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15709) | [PPT 7 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15709) | [Souce Code 7 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15709)


#### Index:
- ###### Processes
    - Process Concept
    - Process Scheduling
    - Operations on Processes
    - Interprocess Communication
    - Examples of IPC Systems
    - Communication in Client – Server Systems

    - **Projects**:    
        - [Creating an interactive user defined shell](https://gist.github.com/pbteja1998/853e5c143136b033e1732f9af81ced62)
        - [Enhancement to your interactive user defined shell](https://gist.github.com/pbteja1998/da3ec4ffb05881d2989ec66df01a9048)
 
- ###### Threads
    - Overview
    - Multithreading Models
    - Thread Libraries
    - Threading Issues
    - Operating-System Examples
- ###### CPU Scheduling
    - Basic Concepts
    - Scheduling Criteria
    - Scheduling Algorithms
    - Thread Scheduling
    - Multiple-Processor Scheduling
    - Thread Scheduling
    - Operating-System Examples
    - Algorithm Evaluation
- ###### Process Synchronization
    - Background
    - The Critical-Section Problem
    - Peterson’s Solution
    - Synchronization Hardware
    - Semaphores
    - Classic Problems of Synchronization
    - Monitors
    - Synchronization Examples
    - Atomic Transactions
- ###### Deadlocks
    - System Model
    - Deadlock Characterization
    - Methods for Handling Deadlocks
    - Deadlock Prevention
    - Deadlock Avoidance
    - Deadlock Detection
    - Recovery from Deadlock
#### **Projects:**
- [Producer Consumer Problem](https://gist.github.com/pbteja1998/e36b85a3058313c02fa945f2baa41fea)
- [Concurrent Merge Sort](https://gist.github.com/pbteja1998/c505fccc37bb6a6534c8e8b7d87eb986)


### Memory Management:
#### Preface from the Book:
<p>
Chapters 8 and 9 deal with main memory management during the execution of a process. To improve both the utilization of the CPU and the speed of its response to its users, the computer must keep several processes in memory. There are many different memory-management schemes, reflecting various approaches to memory management, and the effectiveness of a particular algorithm depends on the situation.
</p>

Chapter | Lecture Slides | Practice Exercises | Powerpoint Presentations | Source Code | Tasks
:-- | :--: | :--: | :--: | :--: | :--
[Main Memory](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15710) | [Lecture 8 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15710) | [Execise 8 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15710) | [PPT 8 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15710) | [Souce Code 8 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15710)
[Virtual Memory](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15711) | [Lecture 9 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15711) | [Execise 9 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15711) | [PPT 9 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15711) | [Souce Code 9 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15711)


#### Index:
- ###### Main Memory
    - Background
    - Swapping
    - Contiguous Memory Allocation
    - Paging
    - Structure of the Page Table
    - Segmentation
    - Example: The Intel Pentium
- ###### Virtual Memory
    - Background
    - Demand Paging
    - Copy-on-Write
    - Page Replacement
    - Allocation of Frames
    - Thrashing
    - Memory-Mapped Files
    - Allocating Kernel Memory
    - Other Considerations
    - Operating-System Examples

#### Open Source Project:
- [Xv6-Project](https://gist.github.com/pbteja1998/b6dbc9415b4a91b02a73790be0415fb0)

### Storage Management:
#### Preface from the Book:
<p>
Chapters 10 through 13 describe how the file system, mass storage, and I/O are handled in a modern computer system. The file system provides the mechanism for on-line storage of and access to both data and programs residing on the disks. These chapters describe the classic internal algorithms and structures of storage management. They provide a firm practical understanding of the algorithms used the properties, advantages, and disadvantages. Since the I/O devices that attach to a computer vary widely, the operating system needs to provide a wide range of functionality to applications to allow them to control all aspects of the devices. We discuss system I/O in depth, including I/O system design, interfaces, and internal system structures and functions. In many ways, I/O devices are also the slowest major components of the computer. Because they are a performance bottleneck, performance issues are examined. Matters related to secondary and tertiary storage are
explained as well.
</p>

Chapter | Lecture Slides | Practice Exercises | Powerpoint Presentations | Source Code | Tasks
:-- | :--: | :--: | :--: | :--: | :--
[File-System Interface](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15712) | [Lecture 10 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15712) | [Execise 10 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15712) | [PPT 10 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15712) | [Souce Code 10 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15712)
[File-System Implementation](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15713) | [Lecture 11 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15713) | [Execise 11 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15713) | [PPT 11 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15713) | [Souce Code 11 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15713)
[Mass-Storage Structure](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15714) | [Lecture 12 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15714) | [Execise 12 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15714) | [PPT 12 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15714) | [Souce Code 12 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15714)
[I/O Systems](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15715) | [Lecture 13 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15715) | [Execise 13 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15715) | [PPT 13 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15715) | [Souce Code 13 ](http://bcs.wiley.com/he-bcs/Books?action=chapter&bcsId=2217&itemId=0471694665&chapterId=15715)


#### Index:
- ###### File-System Interface
    - File Concept
    - Access Methods
    - Directory Structure
    - File-System Mounting
    - File Sharing
    - Protection
- ###### File-System Implementation
    - File-System Structure
    - File-System Implementation
    - Directory Implementation
    - Allocation Methods
    - Free-Space Management
    - Efficiency and Performance
    - Recovery
    - Log-Structured File Systems
    - NFS
    - Example: The WAFL File System
- ###### Mass-Storage Structure
    - Overview of Mass-Storage Structure
    - Disk Structure
    - Disk Attachment
    - Disk Scheduling
    - Disk Management
    - Swap-Space Management
    - RAID Structure
    - Stable-Storage Implementation
    - Tertiary-Storage Structure
- ###### I/O Systems
    - Overview
    - I/O Hardware
    - Application I/O Interface
    - Kernel I/O Subsystem
    - Transforming I/O Requests to Hardware Operations
    - STREAMS
    - Performance

## <p align="center">Final project</p>

You are encouraged to do the assignments and exams for each course, but what really matters is whether you can *use* your knowledge to solve a real world problem.

After you've gotten through all of  the parts of the curriculum relevant to you, you should think about a problem that you can solve using the knowledge you've acquired.
Not only does real project work look great on a resume, the project will *validate* and *consolidate* your knowledge.

## <p align="center">Evaluation</p>

Upon completing your final project, submit your project's information to [PROJECTS](PROJECTS.md)
via a pull request and use our [community](#community) channels to announce it to your fellow students.

Your peers and mentors from the community will then informally evaluate your project.
You will not be "graded" in the traditional sense — everyone has their own measurements for what they consider a success.
The purpose of the evaluation is to act as your first announcement to the world that you are a developer, and to get experience listening to feedback — both positive and negative — and taking it in stride.

The final project evaluation has a second purpose: to evaluate whether CoderPlex,
through its community and curriculum, is successful in its mission to guide independent learners in obtaining knowledge.

## <p align="center">Cooperative work</p>

You can create these project alone or with other students!
**We love cooperative work**!
Use our [channels](#community) to communicate with other fellows to combine and create new projects!


## <p align="center">Additional Resources</p>



## <p align="center">Open Source Projects</p>