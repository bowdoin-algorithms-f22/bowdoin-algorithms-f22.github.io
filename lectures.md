---
layout: default 
title:  --Weekly schedule and lectures
nav_order: 4
---


## Week by week  schedule and lectures (Spring'22)


### Week 1: Introduction and warmup (bubble sort, insertion sort, selection sort). Asymptotic analysis basics.

_Jan 24-28_

We start by reviewing two fundamental problems---searching and sorting---and going over a couple of simple algorithms. We also review the basics of algorithms analysis using big-oh notation, as well as best-cases and worst-cases.  You are probably familiar with most of this content from Data Structures (if this  content is new, you'll need to budget more time this first week to understand these new concepts). 

__Objectives:__ By the end of this  week you should be able to: 
  * Understand searching (linear search, binary search) and simple sorting (bubble sort, selection sort, insertion sort) and be able to compare them, analyze them and apply  them to various inputs
  * Understand the basics of algorithm analysis, big-Oh notation best-case and worst-case analysis

__Resources:__     
  * __Lecture:__ [LN-warmup.pdf](docs/week1-LN-warmup.pdf) 
       * __Slides and videos:__    see Blackboard    
       * __Precheck:__  see Blackboard      
  *  __Lab:__   [Lab 1](docs/lab1.pdf)
  * __Quiz:__    Quiz1  (on Blackboard)
  * __Assignment:__ Assignment1 (on Gradescope)
  
 ***
 
 
 
### Week 2: Asymptotic Notation and Summations

_Jan 31- Feb 4_

Joke: An infinite number of computer scientists walk into a bar. The first one orders a beer. The second one, half a beer. The third one, a quarter. The barman pours two beers. The computer scientists complain: Is that all you're giving us? The barman says: "Come on guys, you should know your limits! "

The goal of weeks 2, 3 is to give you the conceptual tools  to analyze algorithms.  This week (week 2) we start by introducing the concepts of "asymptotic" analysis  and "order of growth". The order of growth is analyzed with O(), Ω() and Θ() notation. We'll give a formal definition of each one and discuss the differences between them and why big-oh is not sufficient. 

When analyzing algorithms it is common to encounter the so-called "summations".  In fact, you already encountered a summation when you tried to analyze Selection Sort or Insertion Sort!  We introduce the two basic summations that come up most often in the analysis of algorithms: arithmetic and geometric summations. 

This part of the class is heavy on discrete math like logarithms, exponents, limits and recursive functions, which most of you have not seen in a long time.  Hang in there!  The bright side is that there are formulas and rules for everything and it's just a matter of practice.  Really.  Give yourself time to practice and expect it will take time.  I have included many exercises and examples  which will help you through.  It is really important that you budget plenty of time. 

If you are not fond of analysis, I have some good news: once this module is over, you'll know enough to be able to analyze pretty much anything!  The remaining of the semester will be focused on new algorithms.  If you like analysis, I have some good news for you as well:  In the next modules you'll see analysis tools at work on some pretty neat algorithms.  


__Objectives:__ By the end of this  week you should be able to: 
* Understand the relevance of analysis in practice, as well as its assumptions and limitations
* Understand the definitions of O(), Ω(), Θ()
* Understand the rate of growth of common functions
* Find the rate of growth of a function
* Compare the order of growth of two arbitrary functions f(n), g(n)
* Analyze basic algorithm running times using O(), Ω(), Θ() 
* Understand arithmetic and geometric summations and their Θ() bound 
* Recognize arithmetic and geometric summations in different forms and give Θ() bounds


__Resources:__    
  * __Lecture:__ [LN-asymptoticNotation.pdf](docs/week2-LN-asymptoticNotation.pdf),  [LN-summations.pdf](docs/week2-LN-summations.pdf)
  * __Slides and videos:__ see Blackboard      
  * __Precheck:__  see Blackboard
  * __Lab:__   [Lab2](docs/lab2.pdf) 
  * __Quiz:__ [quiz2-practice.pdf](docs/week2-quiz-practice.pdf),   Quiz2: see Blackboard
  * __Assignment:__  Assignment 2 (on Gradescope)
  
***
   
   
   
   
   
### Week 3: Mergesort and Recurrences
_Feb 7-11_

This week we continue with the topic of analysis and  introduce  the "recurrence" to express the running time of recursive algorithms. To motivate the first recurrence, we introduce a new sorting algorithm called Mergesort.  We express the running time of Mergesort   using a recurrence, which solves to O(n lg n).  Mergesort is the first algorithm we see in this class which beats the quadratic sorting algorithms from  previous lectures. 

__Objectives:__ By the end of this  week you should be able to: 
* Understand Mergesort: how it works, why it works, and its running time analysis
* Understand how to express the running time of recursive algorithms using recurrences
* Solve recurrences by repeated iteration
* Recognize broadly classes of recurrences ( logarithmic, linear, Θ(n lg n), exponential)

__Resources:__    
  * __Lecture:__ [LN-recurrences.pdf](docs/week3-LN-recurrences.pdf)
  	* __Slides and videos:__    see Blackboard    
  	* __Precheck:__  see Blackboard     
  * __Lab:__   [Lab3](docs/lab3.pdf) 
  * __Quiz:__ [quiz3-practice.pdf](docs/week3-quiz-practice.pdf) ; Quiz3: see Blackboard
  * __Assignment:__ Assignment 3 (on Gradescope)
   
 ***



### Week 4: Heapsort and Quicksort
_Feb 14-18_

So far we have discussed tools necessary for analyzing algorithms (asymptotic notation, summations and recurrences) and we have seen a couple of sorting algorithms at work. This week we introduce new sorting algorithms: Heapsort, Quicksort, and it's randomized version, Randomized-Quicksort. Heapsort is based on the heap, which is the standard implementation of a priority queue. Randomized-Quicksort is considered the most efficient general-purpose sorting algorithm in practice.

__Objectives:__ By the end of this  week you should be able to: 
* Understand the interface of a Priority Queue
* Understand how heaps are defined, the operations supported by a heap (Find-Min, DeleteMin, Insert, Heapify, Buildheap) and their Θ() bounds
* Understand Heapsort
* Understand Quicksort and its analysis
* Understand Randomized-Quicksort and its analyzis

__Resources:__     
* __Lecture notes:__ [LN-heapsort.pdf](docs/week4-LN-heapsort.pdf), [LN-quicksort.pdf](docs/week4-LN-quicksort.pdf)
	* __Slides:__  [slides-heaps.pdf](docs/week4-slides-heaps.pdf) ; [slides-quicksort.pdf](docs/week4-slides-quicksort.pdf)
	* __Videos:__   see Blackboard  
	* __Precheck:__  see Blackboard
* __Lab:__   [Lab4](docs/lab4.pdf) 
* __Quiz:__      Quiz4 see Blackboard
* __Assignment:__ Assignment 4  (on Gradescope)

 ***
  
  
  
### Week 5: Sorting lower bound. Faster sorting. Selection. 
_Feb 21-25_

We have seen the most important  sorting algorithms so far and all of them have worst-case running time at least Ω(n lg n). The natural question to ask is: Can we do better than Θ(n lg n) in the worst-case? We introduce the concept of lower bound, and show that sorting lower bound in the comparison model of computation is Ω(n lg n). We describe a couple of different ways to sort which do not use the comparison model and under certain assumptions achieve linear time (bucket sort and counting sort). This concludes the module on sorting. 

This week we introduce a new problem: the __selection__ problem.  Given a set S of n elements, {x_1, x_2, ..., x_n} and an integer k (1 ≤ k ≤ n), find the kth smallest element in S. We describe several ideas for solving this problem, culminating with an elegant and ingenious algorithm that runs in O(n) worst-case.

__Objectives:__ By the end of this  week you should be able to: 
* Understand the comparison-based sorting lower bound, when it applies and what assumptions it makes
* Understand BucketSort and CountingSort,  their analysis and assumptions
* Understand the selection problem, and the algorithms for it (quick-select and smart-select)

__Resources:__     
  * __Lecture notes:__ [LN-linsort.pdf](docs/week5-LN-linsort.pdf), [LN-selection.pdf](docs/week5-LN-selection.pdf)
    * __Slides and videos:__    see Blackboard   
    * __Precheck:__  see Blackboard    
 * __Lab:__   [Lab5](docs/lab5.pdf) 
 * __Quiz:__      Quiz5 see Blackboard
 * __Assignment:__ Assignment 5 (on Gradescope)
 *          
 ***



### Week 6: Problems 
_Feb 28-March 4_

At this point  in the class   (1) you have the tools to analyze algorithms and you appreciate the interplay between analysis and design (what we mean by this is that analyzing your ideas gives you further ideas for how to improve on your initial ideas!);   and (2) you have seen some fundamental algorithms and building blocks---sorting, priority queues and selection.  One of the  goals of this  class is to provide the conceptual  tools for solving new problems on your own. This week we'll take a break from new content and work on  problem solving.  

This week there is no new content (no lecture notes,  no videos and no precheck).   The work for this week consists of  a set of Jupyter notebooks which provide implementation and visualization of some of the algorithms discussed so far; use them to refresh your programming and to deeper understand the algorithms.  And set of new problems to solve. 

__Objectives:__ This week's objective is algorithmic problem solving.  By the end of this week,
* Connect the algorithms discussed so far with their implementation. 
* You would have seen examples of new problems, which may seem like they have nothing to do with the content in the previous weeks;  yet, the process of coming up with solutions to these problems on your own illustrates the very nature of  algorithmic problem solving 
* You understand that algorithmic problem solving is both a science and an art 
* Hopefully, you would have had one "ahaa!" moment 


__Resources:__
  * __Lecture notes:__ [python-mysterySort.ipynb](docs/week6-mysterySort.ipynb), [python-insertionSort.ipynb](docs/week6-insertionSort.ipynb), [python-mergeSort.ipynb](docs/week6-mergesort.ipynb), [python-quickSort.ipynb](docs/week6-quickSort.ipynb)
     * __Slides and videos:__    see Blackboard   
     * __Precheck:__  see Blackboard    
  * __Lab:__   [Lab6](docs/lab6.pdf) 
  * __Quiz:__    Quiz6  see Blackboard
  * __Assignment:__. Assignment 6 (on Gradescope)
    
 ***
 
 
 
### Week 7: Divide-and-conquer
_March 7-11_

What do you do when you encounter a new problem and you don't know how to start?  Coming up with solutions is both an art and a science, and although there are no recipes, there are some techniques that come up frequently.  By now you have some practice, and you perhaps noticed that some of the problems have similar solutions. We'll spend the next three weeks looking at more problems,  grouped by the technique used to solve them. 

This week we introduce a  technique called __divide-and-conquer__. In fact you already saw this technique at work in Mergesort. This week we give more examples of problems that can be  solved via divide-and-conquer, including the famous Strassen's matrix multiplication algorithm. 

__Objectives:__ By the end of this  week you should be able to: 
* Understand how  D&C works in general 
* Understand the algorithms for integer multiplication and matrix multiplication
* Be able to apply D&C to new problems

__Resources:__
  * __Lecture notes:__ [LN-divideAndConquer.pdf](docs/week7-LN-divideAndConquer.pdf)
     * __Slides and videos:__    see Blackboard   
     * __Precheck:__  see Blackboard    
  * __Lab:__   [Lab7](docs/lab7.pdf)
  * __Quiz:__      Quiz7 see Blackboard
  * __Assignment:__ Assignment 7 (on Gradescope) 
         
 ***
 
## Spring break!

***

### Week 8: Dynamic Programming 
_Mar 28 - Apr 1_

This week we introduce the technique called _dynamic programming_ and see it at work on  three problems: Fibonacci, board game and rod cutting. 

__Objectives:__ By the end of this  week you should be able to: 
* Understand  the basic principles of dynamic programming  
* Understand the three examples discussed in the lecture notes (including correctness and analysis) 
* Move towards applying DP to new problems 

__Resources:__
* __Lecture notes:__ [LN-dynprog.pdf](docs/week8-LN-dynprog.pdf), [LN-rod.pdf](docs/week8-LN-rod.pdf), [rod-summary.pdf](docs/summary-rod.pdf)
    * __Slides and videos:__    see Blackboard   
    * __Precheck:__  see Blackboard    
* __Lab:__   [Lab8](docs/lab8.pdf) 
* __Quiz:__    Quiz8  see Blackboard
* __Assignment:__ Assignment 8  (on Gradescope)
   
  
 ***
 
 
 
### Week 9: More DP examples; Greedy algorithms 
_Apr 4-8_

This week we add more ddynamic programming examples, and we introduce the greedy technique via the _activity selection_ problem. 

__Objectives:__ By the end of this  week you should be able to: 
* Understand the knapsack problem 
* Understand  how  the greedy technique works in general and contrast it with DP
* Understand the greedy solution for the example discussed in the lecture notes (activity selection), including the correctness proof 
* Move towards  applying the greedy technique to new problems 

__Resources:__
* __Lecture notes:__ [LN-knapsack.pdf](docs/week8-LN-knapsack.pdf), [knapsack.pdf](docs/summary-knapsack.pdf), [LN-greedy.pdf](docs/week9-LN-greedy.pdf)
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard    
* __Lab:__   [Lab9](docs/lab9.pdf) 
* __Quiz:__      Quiz9 see Blackboard     
* __Assignment:__
    * Assignment 9 (on Gradescope)
   
 ***




### Week 10: 
_Apr 11-15_

This week we'll wrap up the module on algorithmic techniques ---divide and conquer, dynamic programming, and greedy---by seeing  a couple more examples of  these techniques at work. 

__Objectives:__ By the end of this  week you should be able to: 
* Reflect on the problems we've looked at and compare on how the general technique was instantiated  for that specific problem. 
* At this point the problems we've seen should feel familiar, and the goal is be  to be able to come up with the algorithms on your own. 

__Resources:__
* __Lecture notes:__ [LN-lcs.pdf](docs/week10-LN-lcs.pdf) ; [LN-review.pdf](docs/week10-LN-review.pdf)
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard    
* __Lab:__   [Lab10](docs/lab10.pdf) 
* __Quiz:__   Quiz10 (in class) 
* __Assignment:__ Assignment 10  (on Gradescope)

***



### Week 11: Graphs: Basics, BFS and DFS
_Apr 18-22_

We've reached the last module this semester, graphs. Once you learn about graphs, you start to see their applications  everywhere around!  This week we start with basic terminology and the traversals, breadth-first and depth-first. These simple algorithms are the stepping stone to many other problems. 

__Objectives:__ By the end of this  week you should be able to: 
* Compare and contrast the adjacency list and adjacency matrix representation of a graph 
* Compare and contrast different types of graph: sparse, complete, dense, trees
* Understand basic graph problems:  path, connectivity, connected components, reachability
* Understand breadth-first and depth-first traversals, their complexity,  and their properties 

__Resources:__
* __Lecture notes:__ [LN-graphBasics.pdf](docs/week11-LN-basics.pdf), [LN-bfsdfs.pdf](docs/week11-LN-bfsdfs.pdf)
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard    
* __Lab:__   [Lab11](docs/lab11.pdf) 
* __Quiz:__    Quiz11  (see Blackboard)
* __Assignment:__ [Assignment 11](docs/hw11.pdf)  (on Gradescope)     

***
 
 
 
### Week 12 :  Application of BFS and DFS. Topological order. Shortest paths on DAGs.  
_Apr 25-29_

This week  we introduce the problem of a computing topological order on a directed acyclic graph (DAG).  Then we look at how  topological order can be used to solve various other problems on DAGs, including a simple algorithm for  computing shortest paths on a DAG. 

__Objectives:__ By the end of this  week you should be able to: 
* Understand the applications of graph traversal to basic problems on directed and undirected graphs
* Understand  the concept of topological order
* Understand the algorithms for computing topological order 
* Use topological order for dynamic programming on DAGs
* Understand the properties of shortest paths and how SP can be computed on a DAG

__Resources:__
* __Lecture notes:__ [LN-topsort.pdf](docs/week12-LN-topsort.pdf)
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard  
* __Lab:__   [Lab12](docs/lab12.pdf)  
* __Quiz:__   Quiz12   (see Blackboard)  
* __Assignment:__ [Assignment 12](docs/hw12.pdf)  (on Gradescope)
  
 ***
 
 
 
 
### Week 13: Shortest paths. 
_May 2-6_

This week we discuss computing shortest paths in graphs, and see some of the nicest algorithms in Computer's Science: Dijkstra's algorithm and Bellman-Ford's algorithm. While describing them we try to understand some common principles that guided their design.
Bellman-Ford's algorithm uses dynamic programming and Dijkstra's algorithm is a greedy algorithm.   These are new applications of the problem solving techniques we discussed in the previous weeks! 

__Objectives:__ By the end of this  week you should be able to: 
* Understand the algorithms for computing shortest paths explained in the notes:  how they work, why they work, and their complexity

__Resources:__
* __Lecture notes:__ [LN-shpaths.pdf](docs/week13-LN-shpaths.pdf)
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard    
*  __Lab:__   [Lab13](docs/lab13.pdf) 
* __Quiz:__   Quiz13   (see Blackboard)    
* __Assignment:__ [Assignment 13](docs/hw13.pdf) (on Gradescope)
                   
 ***
 
 
 
### Week 14: Minimum spanning tree. Final review. 
_May 9-11_

This final week we'll introduce  another fundamental problem on graphs, the Minimum Spanning Tree (MST). We'll see a couple of properties of MSTs which will get us intuition for how to compute an MST efficiently. We'll glance at two well-known algorithms, Prim's and Kruskal's,  which are both greedy algorithms much in the spirit of Dijkstra.  Their correctness follows from a neat result called The Cut Theorem.   

This last week we'll also do a quick review and work on some extra fun problems!

__Objectives:__ By the end of this  week you should be able to: 
* Understand the concept of MST (minimum spaninng tree) in a graph, and be able to answer basic questions about it sproperties
* Know the general idea of Kruskal's and Prim's algorithms, and the Cut Theorem which captures their correctness

__Resources:__
* __Lecture notes:__ [LN-mst.pdf](docs/week14-LN-mst.pdf), [LN-mst-summary.pdf](docs/week14-LN-mst-summary.pdf), [LN-review.pdf](docs/week14-LN-review.pdf),
   * __Slides and videos:__    see Blackboard   
   * __Precheck:__  see Blackboard    
* __Lab:__   [Lab14](docs/lab14.pdf) 
* __Quiz:__   Quiz14  (in class)     
* __Assignment:__  _none_
                      
***




