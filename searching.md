# Top Used Searching Algorithms

## 1. Linear Search
- **Description:** Checks each element sequentially.
- **Time Complexity:** 
  - Best: \(O(1)\)
  - Average/Worst: \(O(n)\)
- **Use Case:** Small or unsorted datasets.

---

## 2. Binary Search
- **Description:** Efficiently finds a target in a sorted array by halving the search space.
- **Time Complexity:**
  - Best/Average/Worst: \(O(\log n)\)
- **Use Case:** Large sorted datasets.

---

## 3. Jump Search
- **Description:** Jumps ahead by fixed steps and performs linear search within blocks.
- **Time Complexity:**
  - Best: \(O(1)\)
  - Average/Worst: \(O(\sqrt{n})\)
- **Use Case:** Sorted arrays with predictable data access.

---

## 4. Exponential Search
- **Description:** Combines binary search with range finding for unbounded lists.
- **Time Complexity:**
  - Best: \(O(1)\)
  - Average/Worst: \(O(\log n)\)
- **Use Case:** Infinite or very large lists.

---

## 5. Interpolation Search
- **Description:** Estimates the position of the target in uniformly distributed sorted arrays.
- **Time Complexity:**
  - Best: \(O(1)\)
  - Average: \(O(\log \log n)\)
  - Worst: \(O(n)\)
- **Use Case:** Uniformly distributed sorted datasets.

---

## 6. Ternary Search
- **Description:** Divides the array into three parts for searching.
- **Time Complexity:**
  - Best/Average/Worst: \(O(\log_3 n)\)
- **Use Case:** When minimizing comparisons is a priority.

---

## 7. Fibonacci Search
- **Description:** Uses Fibonacci numbers to divide the search space.
- **Time Complexity:**
  - Best/Average/Worst: \(O(\log n)\)
- **Use Case:** Sorted arrays avoiding division operations.

---

## 8. Sublist Search (Rabin-Karp Algorithm)
- **Description:** Searches for a substring using hashing.
- **Time Complexity:**
  - Average: \(O(n + m)\)
  - Worst: \(O(nm)\)
- **Use Case:** Text processing and pattern matching.

---

# Summary
- **Linear and Binary Searches** are foundational and widely applied.
- **Binary Search** is preferred for sorted datasets due to its efficiency.
- **Interpolation and Exponential Searches** offer optimizations in specific scenarios.
- **String searching algorithms** like Rabin-Karp are crucial for text processing tasks.
