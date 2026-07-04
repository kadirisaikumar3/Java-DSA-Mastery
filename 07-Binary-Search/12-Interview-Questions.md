# 🎯 Interview Questions

---

# Beginner

### 1. What is Binary Search?

A searching algorithm that repeatedly divides the search space into two halves to find a target efficiently.

---

### 2. What is the Time Complexity of Binary Search?

Average Case

```
O(log n)
```

Worst Case

```
O(log n)
```

---

### 3. What are the prerequisites for Binary Search?

- Sorted Data
- Random Access

---

### 4. Why calculate mid as:

```java
left + (right-left)/2
```

To avoid integer overflow.

---

### 5. Difference between Linear Search and Binary Search?

| Linear Search | Binary Search |
|--------------|---------------|
| O(n) | O(log n) |
| Unsorted Allowed | Sorted Required |

---

# Intermediate

### 6. What is Boundary Binary Search?

A Binary Search variant used to find the first or last occurrence of an element.

---

### 7. What is Lower Bound?

The first index where the element is **greater than or equal** to the target.

---

### 8. What is Upper Bound?

The first index where the element is **greater than** the target.

---

### 9. What is Search on Answer?

Applying Binary Search to the answer space instead of the array.

---

### 10. Why does Binary Search work?

Because the search space is sorted or monotonic.

---

# Google-Level Questions

- Search in Rotated Sorted Array
- Find Peak Element
- Koko Eating Bananas
- Capacity to Ship Packages
- Split Array Largest Sum
- Median of Two Sorted Arrays

---

# Interview Tip

Always explain why one half of the search space can safely be discarded.