---
title: Algorithms 2022/23 (26h, 8 ECTS, Laboratory classes)
summary: B.Sc. in Management and Computer Science, Department of Business and Management, Luiss Guido Carli, Italy
tags:
  - Algorithms
  - Luiss
date: '2023-05-06T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
url_code: '' # change to github
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


**Lecture 1 - Lab**

🡢 First release of the Group Software Project. Here you can find the full description of the first part.

**Lecture 2 - Lab Fibonacci**

🡢 Folder content: Slides, jupyter notebook and solutions. The jupyter notebook contains extra exercises.

**Lecture 3 - slides and exercises**

🡢 Here you can find the slides of the mystery function that we saw today, and the Jupyter notebook file that gives you the skeleton on what you need to implement and evaluate the execution time of each version of the mystery function.
Notice that the base case in the mystery function is if x = 1 then return 2, instead of going until x = 0. The base case x = 1 is equivalent to x = 0 as a stopping criterion for calculating 2x . Notice however, that for x = 1 we return 2 (because 21 = 2) and for x = 0 we return 1 (because 20 = 1). This simple change in the base case, makes your execution time (on the non-improved mystery function) 2x-1 instead of 2x. You may think "oh cool" my algorithm is more efficient and faster since you've got rid of an entire layer of recursion in the tree of recursive calls. Well, you'll soon learn (this Thursday) that, theoretically, both algorithms have the same execution time. Big O notation coming towards you :-)

**Lecture 4 - Lab Bubble Sort**

🡢 This lecture is about asymptotic notation and Bubble Sort.

**Lecture 5 - Lab binary search and counting in logn**

🡢 Binary search is an algorithm used to search for a specific value in a sorted list or array. The algorithm works by repeatedly dividing the search interval in half, eliminating the half that does not contain the target value, until the value is found or the interval is empty. It's a very efficient search algorithm, as the number of comparisons needed to find the target value is logarithmic in the size of the array. In other words, it can quickly find the target value in a large array with fewer comparisons than other search algorithms.

🡢 Exercise: Try to modify the last count based on binary search to also consider the negative of the target element given in input. Example: when searching for 2, you need to think about -2 as well, and return the sum of the occurrences. Try to improve upon the naive approach.

**Lecture 6 - Lab Fibonacci and Ternary search complexity**

**Lecture 7 - Lab Software Project part 2**

🡢 Second release of the Group Software Project. Here you can find the full description of the first part.

**Lecture 8 - Lab FAANG coding interview part 1**

🡢 Coding interview part 1 containing three problems of which one is hard and requires you to critically think about your solution.

**Lecture 9 - Lab Merge Sort**

**Lecture 10 - Lab FAANG coding interview part 2 & 3**

🡢 Coding interview part 2 & 3 containing several problems of medium difficulty that we solve during the classes. Pay attention to the last problem. Here, we're using an informal way of what a min-heap is. We'll discuss this tomorrow (24/03).

**Lecture 11 - Lab Quick Sort a step-by-step example**

**Lecture 12 - Lab Heaps and applications: priority queues**

**Lecture 13 - FAANG interview part 4**

🡢 Here we treated two different problems:

1. Merge k linked lists -> we saw how to maintain the head of a linked list unvaried while populating the next element

2. Pancake sorting -> we saw how we can put the maximum element at the beginning of the array and then flip it

🡢 Here you'll also find a third problem which uses prefix- and suffix-sum. Before seeing the optimized solution, try to find a naïve one by yourself. 

🡢 Exercise: What's the time complexity of my solution and what the time complexity of your naïve solution?

**Lecture 14 - Trees and visits**

As highly anticipated in our last lectures, we're going to treat trees today! Here we define a binary tree in 3 lines of Python code! We cover the Depth First Search (DFS) type of visiting the nodes of a binary tree, and we explore three types of node traversal policies that enable us to solve different problems. You'll find two exercises that we'll solve together using DFS.

**Lecture 15 - Lab Software Project part 3**

**Lecture 16 - Challenging BST Exercises**

🡢 We'll delve deep into Binary Search Trees (BSTs) with some challenging exercises.

**Lecture 17 - Lab Graphs and Dijkstra Algorithm step-by-step**

**Lecture 18 - Expression Tree (solution to HW3) + Minimum Spanning Tree**

🡢 Solution to the expression tree evaluation exercise in Homework 3. We'll find out why Python is dangerous 😂😰

🡢 How to build a minimum spanning tree (MST) from a weighted graph.

**Lecture 19 - Lab Graph exercises**
