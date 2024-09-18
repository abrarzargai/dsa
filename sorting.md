## Sorting Algorithms Cheat Sheet

### Basic Sorting Algorithms
- **Bubble Sort** Swap adjacent elements until sorted  \(O(n^2)\)  
- **Selection Sort**  Select the smallest element and swap to the front  \(O(n^2)\)  
- **Insertion Sort**   Insert each element in its correct position   \(O(n^2)\)  

### Efficient Sorting Algorithms
- **Merge Sort**
- **Quick Sort**
- **Heap Sort**

### Advanced Sorting Algorithms
- **Counting Sort**
- **Radix Sort**
- **Bucket Sort**

---

### What is Bubble Sort?
- **Description:** Compares and swaps neighboring elements. 🔄
- **Visualization Example:**  
  For **[5, 3, 8, 4]**  
  - Loop 1: [3, 5, 4, 8]  
  - Loop 2: [3, 4, 5, 8]  
- **Best Case:** \(O(n)\) (sorted)  
- **Use:** Small lists, teaching, nearly sorted lists.  

### What is Insertion Sort?
- **Description:** Builds the sorted list one element at a time. 🔄
- **Visualization Example:**  
  For **[5, 3, 8, 4]**  
  - Insert 3 → [3, 5, 8, 4]  
  - Insert 4 → [3, 4, 5, 8]  
- **Best Case:** \(O(n)\) (sorted)  
- **Use:** Small or partially sorted lists, limited memory.  

### What is Selection Sort?
- **Description:** Selects the smallest element and moves it to the front. 🔄
- **Visualization Example:**  
  For **[29, 10, 14, 37, 13]**  
  - Swap 10 → [10, 29, 14, 37, 13]  
  - Swap 13 → [10, 13, 14, 37, 29]  
- **Best Case:** \(O(n^2)\)  
- **Use:** Small lists, simple implementations.  

---

### Memory Aids
- **Bubble Sort:** "Swap Neighbors!" 🛁
- **Selection Sort:** "Select and Swap!" 🏷️
- **Insertion Sort:** "Insert in Place!" 🛠️
