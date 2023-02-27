# Sorting Algorithms

## Overview
Implementing the following sorts and compares the performance for operations on vectors of integers of growing sizes 10, 100, 1000, 5000, 10000, 25000, etc....

1. BubbleSort
2. InsertionSort
3. MergeSort
4. Non-Recursive, one extra vector MergeSort (We’ll call this improved version, IterativeMergeSort from here on out in this homework)
5. QuickSort
6. ShellSort

## Analysis
The performances of each sorting algorithm based on the time running with increasing data size, in order from the fastest to the slowest is:
1.	QuickSort
2.	MergeSort
3.	ShellSort
4.	IterativeMergeSort
5.	InsertionSort
6.	BubbleSort

## Big-O 
### QuickSort
Worst case: O(n^2)
Average case: O(n log n)
### MergeSort
Worst case: O(n log n)
Average case: O(n log n)
### ShellSort
Worst case: O(n^2)
Average case: O(n^(3/2))
### IterativeMergeSort
Worst case: O(n log n)
Average case: O(n log n)
### InsertionSort
Worst case: O(n^2)
Average case: O(n^2)
### BubbleSort
Worst case: O(n^2)
Average case: O(n^2)

We know that O(n log n) is faster than O(n^2): n log n < n^2
O(n^(3/2)) = O(n * n^(1/2). n * n^(1/2) < n^2
Depending on the vector size, different sorting algorithms can have different time complexity:
All algorithms take approximately the same time for vector size less than 10. 
O(n^2) works fine with vector size 10,000, but slower with size 1,000,000. 
O(n log n) are helpful with vector up to size 1,000,000.  
