## 🧠 C - Sorting Algorithms & Big O

### 🔹 What is a sorting algorithm?

A **sorting algorithm** is a method used to reorder elements (like numbers) in a specific order — usually ascending or descending. Sorting makes it easier to search, analyze, and display data.

---

### 🔹 Why is sorting important?

- Makes searching faster (e.g., binary search)
- Organizes data for better readability
- Essential for other algorithms (merge, filter, etc.)

---

### 🔹 Examples of sorting algorithms in C

- **Bubble Sort**: Compares and swaps adjacent elements. Simple but slow.
- **Insertion Sort**: Inserts elements into the correct position one by one. Great for small or nearly sorted data.
- **Selection Sort**: Selects the smallest element and places it in order.
- **Quick Sort**: Divide-and-conquer approach. Fast but not stable.
- **Merge Sort**: Divide-and-conquer with extra space. Stable and efficient.

---

### 🔹 Time Complexity (Big O)

| Algorithm       | Best Case | Average Case | Worst Case |
|----------------|-----------|--------------|------------|
| Bubble Sort     | O(n)      | O(n²)         | O(n²)       |
| Insertion Sort  | O(n)      | O(n²)         | O(n²)       |
| Selection Sort  | O(n²)     | O(n²)         | O(n²)       |
| Quick Sort      | O(n log n)| O(n log n)    | O(n²)       |
| Merge Sort      | O(n log n)| O(n log n)    | O(n log n)  |

---

### 🔹 Common Big O Notation Meanings

- **O(1)** → Constant time: execution time does not change with input size.
- **O(n)** → Linear time: time increases proportionally with input size.
- **O(n²)** → Quadratic time: time grows exponentially with input size. Bad for large data.
- **O(log n)** → Logarithmic time: input size is cut in half each iteration.
- **O(n log n)** → Linearithmic time: most efficient for general-purpose sorting.

