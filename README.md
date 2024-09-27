# dsa

# Data Structures and Algorithms (DSA) Roadmap

# Learn About Complexities

## Time Complexity
- **Concept**: Measures the amount of time an algorithm takes to complete as a function of the input size. OR relation between input size and execution time
- **Examples**: O(1), O(log n), O(n), O(n log n), O(n²)

## Space Complexity
- **Concept**: Measures the amount of memory an algorithm uses as a function of the input size.
- **Examples**: O(1), O(n), O(n²)

## Big-O Notation (Ο)
- **Concept**: Represents the worst-case complexity of an algorithm
- **Examples**: O(1) (Constant Time), O(n) (Linear Time), O(n log n) (Log-Linear Time), O(n²) (Quadratic Time)

## Omega Notation (Ω)
- **Concept**: Represents the best-case complexity of an algorithm
- **Examples**: Ω(1) (Constant Time), Ω(n) (Linear Time)

## Theta Notation (θ)
- **Concept**: Represents the average-case complexity of an algorithm
- **Examples**: θ(n) (Linear Time), θ(n log n) (Log-Linear Time)

# Order of time  Complexities:

| Complexity  | Meaning                          | Example               |
|-------------|----------------------------------|-----------------------|
| O(1)        | Runs once                        | Get one list item     |
| O(log n)    | Grows slowly                     | Binary search         |
| O(n)        | Runs for each input item         | Loop through a list   |
| O(n log n)  | Runs faster than n²              | Efficient sorting     |
| O(n²)       | Runs for each item and each item | Bubble sort           | 

# Example for Complexities:

## Understanding O(log n)
 Logarithmic time complexity \( O(\log n) \) measures how many times we can divide a number by 2 until we reach 1.

#### Example: ( n = 32\)
For ( n = 32 ):
- **Calculation:** 
  - ( log_2(32) = 5 )
This means we can halve ( 32 ) **5 times** to reach 1:

1. ( 32 \div 2 = 16 )
2. ( 16 \div 2 = 8 )
3. ( 8 \div 2 = 4 )
4. ( 4 \div 2 = 2 )
5. ( 2 \div 2 = 1 )

In total, it takes **5 iterations** to get from \( 32 \) to \( 1 \). This is how logarithmic time complexity works!


## Understanding O(n)

Example: If you have an array of 5 items, the algorithm will iterate **5 times** once for each item. 
 
## Understanding O(n²)

Example: If you have an array of 5 items, the algorithm will iterate **25 times**—5 for each item. 
 

## Understanding O(1)
In \( O(1) \) time complexity, the time taken is constant, regardless of the input size \( n \).
### Example:
Accessing an element in an array by index takes the same time, no matter how large the array is. It’s always a single operation.





































## 1. Sorting Algorithms
### Basic Sorting Algorithms
- Bubble Sort
- Selection Sort
- Insertion Sort

### Efficient Sorting Algorithms
- Merge Sort
- Quick Sort
- Heap Sort

### Advanced Sorting Algorithms
- Counting Sort
- Radix Sort
- Bucket Sort

## 2. Searching Algorithms
### Linear Search
- Basic Linear Search

### Binary Search
- Iterative Binary Search
- Recursive Binary Search

### Search in Data Structures
- Search in Sorted Arrays
- Search in Rotated Sorted Arrays
- Search in 2D Matrix

### Advanced Search Algorithms
- Ternary Search
- Interpolation Search

## 3. Dynamic Programming
### Basic Concepts
- Memoization
- Tabulation

### Classic Problems
- Fibonacci Sequence
- Knapsack Problem
- Longest Common Subsequence (LCS)
- Longest Increasing Subsequence (LIS)
- Matrix Chain Multiplication

### Advanced Problems
- Coin Change Problem
- Edit Distance
- Partition Problem
- Maximum Subarray Sum

## 4. Greedy Algorithms
### Basic Concepts
- Greedy Choice Property
- Optimal Substructure

### Classic Problems
- Activity Selection
- Huffman Coding
- Fractional Knapsack Problem
- Job Sequencing Problem

### Advanced Problems
- Minimum Spanning Tree (Kruskal’s and Prim’s Algorithms)
- Dijkstra’s Shortest Path Algorithm
- TSP (Traveling Salesman Problem) (Approximation)

