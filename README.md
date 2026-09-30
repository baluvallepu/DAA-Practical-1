# PRACTICAL-1

## SUMMARY

In this practical, different sorting algorithms were studied and implemented to understand how data can be arranged in ascending or descending order. The main algorithms considered were Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm follows a different method for arranging the elements and has different time and space requirements. Simple algorithms such as Bubble Sort, Selection Sort, and Insertion Sort are easy to understand and work well for small datasets. Merge Sort and Quick Sort are generally more efficient for handling larger datasets.

## CONCLUSION

Sorting algorithms are important for organizing data and making searching and data processing more efficient. Different algorithms have different advantages and limitations, so no single sorting algorithm is best for every situation. The choice of an appropriate sorting algorithm depends on factors such as the size of the dataset, required performance, available memory, and application requirements.

# PRACTICAL-2

## SUMMARY

In this practical, Linear Search and Binary Search were studied and implemented to understand how elements can be searched in a collection of data. Linear Search checks each element one by one until the required element is found, so it can be used with both sorted and unsorted data. Binary Search works by repeatedly dividing the search area into two parts, making it much faster for large datasets. However, Binary Search requires the data to be sorted before searching.

## CONCLUSION

Linear Search and Binary Search are fundamental searching techniques with different advantages. Linear Search is simple and suitable for small or unsorted datasets, while Binary Search is more efficient for large and sorted datasets. Therefore, the choice between the two depends mainly on the size and arrangement of the data and the performance required by the application.

# PRACTICAL-3

## SUMMARY

In this practical, Heap Sort using a Max Heap was studied and implemented for sorting elements in ascending order. A Max Heap keeps the largest element at the root, and this largest element is repeatedly removed and placed at the end of the array. This process continues until all elements are sorted. Heap Sort has a time complexity of O(n log n) in the best, average, and worst cases, providing consistent performance. It is also an in-place sorting algorithm and uses very little additional memory.

## CONCLUSION

Heap Sort using a Max Heap is an efficient and reliable sorting algorithm. It provides a consistent time complexity of O(n log n) for all cases and requires O(1) auxiliary space, excluding the recursion stack. Although it is not stable, it is useful for applications where predictable performance and memory efficiency are important. Overall, Heap Sort is a suitable algorithm for sorting large datasets efficiently.

# PRACTICAL-4 — FACTORIAL PROBLEM

## SUMMARY

In this practical, the factorial of a given number is calculated using an algorithm. The factorial of a positive integer `n` is the product of all positive integers from 1 to `n`, represented as `n!`. For example, `5! = 5 × 4 × 3 × 2 × 1 = 120`. The factorial problem helps in understanding basic programming concepts such as loops, recursion, input handling, and mathematical operations.

## CONCLUSION

The factorial problem provides a simple way to understand how an algorithm can be used to solve a mathematical problem. It can be implemented using both iterative and recursive approaches. The practical helps in understanding repetition, function calls, and the importance of choosing an efficient approach for solving problems.

# PRACTICAL-7 — COIN CHANGE PROBLEM

## SUMMARY

In this practical, the Coin Change Problem was studied to find the minimum number of coins required to make a given amount. Different coin denominations are considered, and an appropriate method is used to determine the best combination of coins. The problem helps in understanding algorithmic problem-solving and concepts such as dynamic programming and optimization.

## CONCLUSION

The Coin Change Problem demonstrates how algorithms can be used to find an efficient combination of coins for a given amount. Dynamic Programming provides an effective approach for finding the minimum number of coins by solving smaller subproblems and storing their results. This practical helps in understanding optimization techniques and their application to real-world problems.

PRACTICAL-5

Summary :

The 0/1 Knapsack Problem was implemented using the Dynamic Programming technique. The program determines the maximum value that can be placed in a knapsack without exceeding its given capacity. Each item can either be selected or not selected. Dynamic Programming stores the results of smaller subproblems in a table, avoiding repeated calculations and making the solution efficient.

Conclusion :

The Dynamic Programming approach provides an efficient solution to the 0/1 Knapsack Problem. It finds the maximum possible value while keeping the total weight within the specified capacity. The algorithm has O(n × W) time complexity and O(n × W) space complexity. Therefore, Dynamic Programming is a suitable technique for solving the Knapsack Problem when the number of items and capacity are manageable.

PRACTICAL-6

Summary :

The Matrix Chain Multiplication problem was implemented using Dynamic Programming. The algorithm finds the most efficient order for multiplying a sequence of matrices by checking different possible multiplication orders and storing the minimum cost of smaller subproblems. This avoids repeatedly calculating the same subproblems.

Conclusion :

Dynamic Programming provides an efficient solution for the Matrix Chain Multiplication problem. It determines the optimal order of matrix multiplication while minimizing the number of scalar multiplications. The algorithm has a time complexity of O(n³) and a space complexity of O(n²). Thus, it is useful for finding an efficient multiplication order when working with a large sequence of matrices.

PRACTICAL -8

## Summary

 Graphs are useful data structures for representing relationships between objects using **vertices (nodes)** and **edges**. Two fundamental graph-searching techniques are **Depth-First Search (DFS)** and **Breadth-First Search (BFS)**. DFS explores a graph by going as deep as possible along one path before backtracking, while BFS explores all neighboring vertices level by level. Both algorithms can be implemented using adjacency matrices or adjacency lists. DFS generally uses a stack or recursion, whereas BFS uses a queue. These techniques are widely used in path finding, network traversal, connectivity checking, and many other computer science applications.

 ## Conclusion

 The implementation of graphs with **DFS and BFS** provides a strong foundation for understanding graph traversal. DFS is useful when deep exploration and backtracking are required, while BFS is particularly useful for level-wise traversal and finding the shortest path in an unweighted graph. Understanding both algorithms helps in solving various real-world and computational problems efficiently and forms an important part of data structures and algorithms.


