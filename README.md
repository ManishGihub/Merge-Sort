# Merge Sort in Java

A simple implementation of the **Merge Sort Algorithm** in Java using the **Divide and Conquer** approach.

## 📌 Overview

Merge Sort is a popular sorting algorithm that divides an array into smaller subarrays, sorts them recursively, and then merges the sorted subarrays to produce a fully sorted array.

This project demonstrates the implementation of Merge Sort in Java.

## 🚀 Features

* Recursive Divide and Conquer approach
* Efficient sorting for large datasets
* Stable sorting algorithm
* Time Complexity of **O(n log n)**

## 🛠️ Algorithm

### Step 1: Divide

Split the array into two halves until each subarray contains only one element.

### Step 2: Conquer

Recursively sort both halves.

### Step 3: Merge

Merge the sorted halves into a single sorted array.

## 💻 Code Execution

### Input

```java
int arr[] = {6,3,9,5,2,8};
```

### Output

```text
2 3 5 6 8 9
```

## 📊 Time and Space Complexity

| Operation        | Complexity |
| ---------------- | ---------- |
| Best Case        | O(n log n) |
| Average Case     | O(n log n) |
| Worst Case       | O(n log n) |
| Space Complexity | O(n)       |

## 🔍 Example

### Before Sorting

```text
6 3 9 5 2 8
```

### After Sorting

```text
2 3 5 6 8 9
```

## ▶️ How to Run

### Compile

```bash
javac MergeSort.java
```

### Execute

```bash
java MergeSort
```

## 🧠 Key Concepts Used

* Recursion
* Divide and Conquer
* Arrays
* Sorting Algorithms

## 📖 About Merge Sort

Merge Sort was invented by **John von Neumann** in 1945 and remains one of the most efficient comparison-based sorting algorithms. It is widely used when stable sorting is required.

## 🤝 Contributing

Feel free to fork this repository, improve the implementation, and submit a pull request.

## ⭐ Support

If you found this project helpful, consider giving it a **star ⭐** on GitHub.
