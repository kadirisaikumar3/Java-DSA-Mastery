# 🎯 Interview Questions

---

# Beginner

### 1. What is a Heap?

A Heap is a Complete Binary Tree that satisfies the Heap Property.

---

### 2. What is the difference between Min Heap and Max Heap?

- Min Heap → Smallest element at the root.
- Max Heap → Largest element at the root.

---

### 3. Why is a Heap called a Complete Binary Tree?

Because every level is completely filled except possibly the last, which is filled from left to right.

---

### 4. What is Heapify?

Heapify restores the Heap Property after insertion, deletion, or modification.

---

### 5. What is the Time Complexity of Heap operations?

| Operation | Time |
|-----------|------|
| Insert | O(log n) |
| Delete | O(log n) |
| Peek | O(1) |

---

# Intermediate

### 6. Why is Build Heap O(n)?

Because most nodes are near the leaves and require little or no Heapify work.

---

### 7. What is a Priority Queue?

A data structure that removes elements based on priority rather than insertion order.

---

### 8. When should you use a Heap?

- Top K Problems
- Priority Scheduling
- Streaming Data
- Graph Algorithms

---

### 9. Why is searching slow in a Heap?

Because only the Heap Property is maintained; elements are not globally sorted.

---

### 10. Why is Java's PriorityQueue a Min Heap?

Because it always removes the smallest element first unless a custom comparator is provided.

---

# Google-Level Questions

- Kth Largest Element
- Top K Frequent Elements
- Merge K Sorted Lists
- Find Median from Data Stream
- Sliding Window Median
- Task Scheduler

---

# Interview Tip

Always explain:

- Heap Property
- Heap Type
- Time & Space Complexity