# DAA-PRACTICAL
# Practical 1 – Sorting Algorithms

## Analysis

In this practical, I worked with five sorting methods: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. The program creates 100 random numbers and runs each sorting algorithm on the same set of numbers. It also records the time taken by every algorithm.

While comparing them, I found that the simpler sorting methods need more comparisons as the number of elements increases. Merge Sort and Quick Sort use a better approach for handling larger data, so they are usually more efficient.

The time shown by the program can change every time because the numbers are generated randomly and the execution also depends on the computer being used.

## Output

```text
Number of Elements = 100

Bubble Sort Time    : 76 microseconds
Selection Sort Time : 41 microseconds
Insertion Sort Time : 20 microseconds
Merge Sort Time     : 76 microseconds
Quick Sort Time     : 17 microseconds
```

## Conclusion

This practical helped me understand that there is no single sorting method that is best for every situation. Simple algorithms are easy to understand, but faster algorithms become more useful when the amount of data increases.

---

# Practical 2 – Searching Algorithms

## Analysis

In this practical, I compared Linear Search and Binary Search using an array of 100,000 sorted elements. The program asks the user for a value and then searches for that value using both methods. The execution time of each search is also calculated.

Linear Search starts from the beginning and checks the elements one after another. Binary Search takes advantage of the sorted array and keeps reducing the search range. Because of this, Binary Search can find an element much faster when the dataset is large.

## Output

```text
Enter element to search: 50000

Linear Search
Element found at index 49999
Time Taken : 1943 microseconds

Binary Search
Element found at index 49999
Time Taken : 1458 microseconds
```

## Conclusion

From this practical, I understood the main difference between Linear and Binary Search. Linear Search is straightforward and can be used on unsorted data, while Binary Search is much more efficient when the data is already sorted.

---

# Practical 3 – Heap Sort

## Analysis

This practical focuses on sorting using Max Heap and Min Heap. The program first creates a random set of numbers and then makes separate copies for both sorting methods. It measures the time taken by Max Heap Sort and Min Heap Sort.

In Max Heap, the largest value is maintained at the top of the heap. In Min Heap, the smallest value is kept at the top. After performing the heap operations, the program displays the execution time in different units.

## Output

```text
Enter number of elements: 100

========== MAX HEAP SORT ==========
Nanoseconds  : 26990 ns
Microseconds : 26 us

========== MIN HEAP SORT ==========
Nanoseconds  : 46655 ns
Microseconds : 46 us
```

## Conclusion

This practical gave me a better idea of how heap structures can be used for sorting. Both approaches are useful for handling larger datasets, and the actual execution time can change depending on the input and system.

---

# Practical 4 – BFS and DFS

## Analysis

In this practical, I implemented two common graph traversal techniques: **Breadth First Search (BFS)** and **Depth First Search (DFS)**. The program takes the number of vertices and edges from the user, creates the graph, and then performs both traversals from the selected starting vertex.

DFS moves deeper into one path before coming back and checking other paths. BFS, on the other hand, visits the nearby vertices first and then moves to the next level. The program also measures how much time each traversal takes in nanoseconds.

## Sample Output

```text
Enter number of vertices: 5
Enter number of edges: 5
Enter edges (u v):
0 1
0 2
1 3
1 4
2 4
Enter starting vertex: 0

DFS Traversal: 0 1 3 4 2

BFS Traversal: 0 1 2 3 4

Execution Time:
DFS: 5200 ns
BFS: 6100 ns
```

*The traversal order and execution time can change depending on the edges entered and the system.*

## Conclusion

This practical helped me understand how DFS and BFS explore a graph in different ways. DFS is useful when we want to explore a path deeply, whereas BFS is useful when we want to visit vertices level by level. I also learned how the same graph can produce different traversal orders depending on the method used.

---

# Practical 8 – Iterative and Recursive Factorial

## Analysis

In this practical, I compared two ways of calculating the factorial of a number: an iterative method and a recursive method. Both functions calculate the same result, but their working approach is different.

The iterative version uses a loop to multiply the numbers one by one. The recursive version calls the same function again with a smaller value until it reaches the base condition. The program calculates the result using both methods and also records their execution time in nanoseconds.

## Output

```text
Enter a non-negative integer (e.g., 20): 10

--- Results for 10! ---
Iterative Result : 3628800
Iterative Time   : 100 ns
-------------------------------
Recursive Result : 3628800
Recursive Time   : 80 ns
```

*Execution time may be different on different systems.*

## Conclusion

This practical helped me understand the difference between iteration and recursion. Both methods give the same factorial result, but recursion solves the problem by repeatedly calling the function, while iteration uses a loop. I also understood that recursion uses additional call-stack memory compared with the iterative approach.

---

# Overall Analysis

Through these practicals, I worked with different types of algorithms, including sorting, searching, graph traversal, and recursion. Comparing their execution times helped me understand that the way an algorithm is designed can make a noticeable difference, especially when the input size becomes larger.

# Overall Conclusion

These practicals gave me hands-on experience with different algorithmic techniques instead of only studying them theoretically. By implementing the programs and checking their outputs and execution times, I got a clearer idea of how algorithms actually behave when they are executed.
