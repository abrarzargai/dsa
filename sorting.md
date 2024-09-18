## 1. Sorting Algorithms

### Basic Sorting Algorithms
- [x] Bubble Sort
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



## What is Bubble Sort?  
A basic sorting algorithm that compares and swaps adjacent elements. 🔄

### How It Works  
1. Compare the first two elements.  
2. Swap if the first is greater.  
3. Move to the next pair.  
4. Repeat until no swaps occur.  

### Example Visualization  
Consider the list: **[5, 3, 8, 4]**

**Loop 1:**
```
- Compare 5 and 3 → **Swap** → [3, 5, 8, 4]  
- Compare 5 and 8 → No Swap → [3, 5, 8, 4]  
- Compare 8 and 4 → **Swap** → [3, 5, 4, 8]  
```
After Loop 1, we continue swapping from the start of the array, moving elements closer to their correct positions. The largest element (8) is now at the end of the list. ✅

**Loop 2:** 
```
- Compare 3 and 5 → No Swap → [3, 5, 4, 8]  
- Compare 5 and 4 → **Swap** → [3, 4, 5, 8]  
- Compare 5 and 8 → No Swap → [3, 4, 5, 8]  
```
After Loop 2, we continue to move the second-largest element (5) into its correct position, just before the already sorted last element (8). ✅

**Loop 3:**  
```
- Compare 3 and 4 → No Swap → [3, 4, 5, 8]  
- Compare 4 and 5 → No Swap → [3, 4, 5, 8]  
- Compare 5 and 8 → No Swap → [3, 4, 5, 8]  
```
After Loop 3, no swaps occurred, indicating that all elements are in the correct order. Therefore, we stop the sorting process! 🚫


### Time Complexity  
- **Best Case:** \(O(n)\) (already sorted)  
- **Average/Worst Case:** \(O(n^2)\)  

### When to Use  
- Very small lists 📋  
- Teaching basic sorting 📚  
- Nearly sorted lists 🗂️  

### How to Remember  
**"Bubble Sort: Swap Neighbors!"** 🛁➡️ This phrase helps you recall that in Bubble Sort, you only swap adjacent elements to sort the list.
