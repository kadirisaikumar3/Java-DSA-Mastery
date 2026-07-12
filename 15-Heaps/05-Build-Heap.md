# 🏗️ Build Heap

---

# What is Build Heap?

Build Heap converts an unsorted array into a valid Heap.

---

# Efficient Method

Start from the last non-leaf node and apply Heapify Down.

```
Last Non-Leaf Index

(n / 2) - 1
```

Process all internal nodes up to the root.

---

# Example

Array

```
[10, 5, 20, 2, 8]
```

After Build Min Heap

```
[2, 5, 20, 10, 8]
```

---

# Complexity

```
O(n)
```

---

# Why not O(n log n)?

Because nodes near the bottom require fewer swaps, reducing the total work.

---

# Interview Tip

Building a Heap from an array is **O(n)**, not **O(n log n)**—a common interview question.