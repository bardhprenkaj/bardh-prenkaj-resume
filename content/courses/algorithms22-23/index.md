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
url_code: 'https://github.com/flaat/Algorithms-2022-2023-Project' # change to github
url_pdf: 'https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxhbGdvcml0aG1zaWNzMzUzfGd4OjI3ZjYxZjM3MmI1NGNhNmU'
url_slides: 'http://jeffe.cs.illinois.edu/teaching/algorithms/'
url_video: 'https://www.youtube.com/watch?v=ZA-tUyM_y7s&list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


**Lecture 1 - Lab**

🡢 First release of the Group Software Project. Here you can find the full description of the first part.

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/1/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download project {{< staticref "uploads/courses/2022_23/algorithms/1/other.pdf" "newtab" >}}part 1{{< /staticref >}} description.


**Lecture 2 - Lab Fibonacci**

🡢 Folder content: Slides, jupyter notebook and solutions. The jupyter notebook contains extra exercises.

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/2/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/2/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 3 - slides and exercises**

🡢 Here you can find the slides of the **mystery** function that we saw today, and the Jupyter notebook file that gives you the skeleton on what you need to implement and evaluate the execution time of each version of the mystery function.
Notice that the base case in the mystery function is if *x = 1 then return 2*, instead of going until *x = 0*. The base case *x = 1* is equivalent to *x = 0* as a stopping criterion for calculating *2^x*. Notice however, that for *x = 1* we return 2 (because 2^1 = 2) and for *x = 0* we return 1 (because 2^0 = 1).

**This simple change in the base case, makes your execution time (on the non-improved mystery function) 2^{x-1} instead of 2^x.** 

You may think "oh cool" my algorithm is more efficient and faster since you've got rid of an entire layer of recursion in the tree of recursive calls. Well, you'll soon learn (this Thursday) that, theoretically, both algorithms have the same execution time. Big O notation coming towards you 😂

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/3/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/3/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 4 - Lab Bubble Sort**

🡢 This lecture is about asymptotic notation and Bubble Sort.

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/4/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/4/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 5 - Lab binary search and counting in logn**

🡢 Binary search is an algorithm used to search for a specific value in a sorted list or array.

The algorithm works by repeatedly dividing the search interval in half, eliminating the half that does not contain the target value, until the value is found or the interval is empty. It's a very efficient search algorithm, as the number of comparisons needed to find the target value is logarithmic in the size of the array. In other words, it can quickly find the target value in a large array with fewer comparisons than other search algorithms.

🡢 **Exercise: Try to modify the last count based on binary search to also consider the negative of the target element given in input. Example: when searching for 2, you need to think about -2 as well, and return the sum of the occurrences. Try to improve upon the naive approach.**

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/5/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 6 - Lab Fibonacci and Ternary search complexity**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/6/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

**Lecture 7 - Lab Software Project part 2**

🡢 Second release of the Group Software Project. Here you can find the full description of the first part.

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/7/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download project {{< staticref "uploads/courses/2022_23/algorithms/7/other.pdf" "newtab" >}}part 2{{< /staticref >}} description.

**Lecture 8 - Lab FAANG coding interview part 1**

🡢 Coding interview part 1 containing three problems of which one is hard and requires you to critically think about your solution.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/8/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 9 - Lab Merge Sort**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/9/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/9/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 10 - Lab FAANG coding interview part 2 & 3**

🡢 Coding interview part 2 & 3 containing several problems of medium difficulty that we solve during the classes. **Pay attention to the last problem. Here, we're using an informal way of what a min-heap is. We'll discuss this tomorrow (24/03).**

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/10/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 11 - Lab Quick Sort a step-by-step example**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/11/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

**Lecture 12 - Lab Heaps and applications: priority queues**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/12/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

**Lecture 13 - FAANG interview part 4**

🡢 Here we treated two different problems:

1. Merge k linked lists -> we saw how to maintain the head of a linked list unvaried while populating the next element

2. Pancake sorting -> we saw how we can put the maximum element at the beginning of the array and then flip it

🡢 **Here you'll also find a third problem which uses prefix- and suffix-sum. Before seeing the optimized solution, try to find a naïve one by yourself.** 

🡢 **Exercise:** What's the time complexity of my solution and what the time complexity of your naïve solution?

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/13/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 14 - Trees and visits**

As highly anticipated in our last lectures, we're going to treat trees today! Here we define a binary tree in 3 lines of Python code! We cover the Depth First Search (DFS) type of visiting the nodes of a binary tree, and we explore three types of node traversal policies that enable us to solve different problems. You'll find two exercises that we'll solve together using DFS.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/14/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 15 - Lab Software Project part 3**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/15/slides.pptx" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download project {{< staticref "uploads/courses/2022_23/algorithms/15/other.pdf" "newtab" >}}part 2{{< /staticref >}} description.

**Lecture 16 - Challenging BST Exercises**

🡢 We'll delve deep into Binary Search Trees (BSTs) with some challenging exercises.

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/16/slides.pdf" "newtab" >}}slides{{< /staticref >}}.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/10/code.zip" "newtab" >}}code{{< /staticref >}}.


**Lecture 17 - Lab Graphs and Dijkstra Algorithm step-by-step**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/17/slides.pdf" "newtab" >}}slides{{< /staticref >}}.


**Lecture 18 - Expression Tree (solution to HW3) + Minimum Spanning Tree**

1. Solution to the expression tree evaluation exercise in Homework 3. We'll find out why Python is dangerous 😂😰

2. How to build a minimum spanning tree (MST) from a weighted graph.

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/courses/2022_23/algorithms/18/code.ipynb" "newtab" >}}code{{< /staticref >}}.

**Lecture 19 - Lab Graph exercises**

{{< icon name="download" pack="fas" >}} Download {{< staticref "uploads/courses/2022_23/algorithms/19/slides.pdf" "newtab" >}}slides{{< /staticref >}}.
