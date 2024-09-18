## 1. Sorting Algorithms

### Basic Sorting Algorithms
- [x] Bubble Sort
- [ ] Selection Sort
- [x] Insertion Sort

### Efficient Sorting Algorithms
- Merge Sort
- Quick Sort
- Heap Sort

### Advanced Sorting Algorithms
- Counting Sort
- Radix Sort
- Bucket Sort



# What is Bubble Sort?  (Swap Neighbors)
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

# What is Insertion Sort?  (sort the one element at a time)
A simple sorting algorithm that builds the final sorted array one element at a time. 🔄

### How It Works  
1. Start with the second element (assume the first is sorted).
2. Compare it to the elements before it.
3. Shift larger elements one position to the right.
4. Insert the current element in its correct position.
5. Repeat until the entire list is sorted.

### Example Visualization  
Consider the list: **[5, 3, 8, 4]**

**Loop 1:**  
- Start with the second element (3).  
- Compare 3 with 5 → **Shift** 5 → [5, 5, 8, 4]  
- Insert 3 → [3, 5, 8, 4]  

**Loop 2:**  
- Move to the next element (8).  
- Compare 8 with 5 → No Shift → [3, 5, 8, 4]  
- 8 is already in the correct position.  

**Loop 3:**  
- Move to the last element (4).  
- Compare 4 with 8 → **Shift** 8 → [3, 5, 8, 8]  
- Compare 4 with 5 → **Shift** 5 → [3, 5, 5, 8]  
- Insert 4 → [3, 4, 5, 8]  

After all loops, the list is sorted: **[3, 4, 5, 8]**! ✅

### Time Complexity  
- **Best Case:** \(O(n)\) (already sorted)  
- **Average/Worst Case:** \(O(n^2)\)  

### When to Use  
- Small or partially sorted lists 📋  
- When memory space is limited 💾  
- Adaptive situations (where elements are often added) ➕  

### How to Remember  
**"Insertion Sort: Insert in Place!"** 🛠️➡️ This phrase helps you recall that Insertion Sort places each element in its correct position within the sorted part of the list.
