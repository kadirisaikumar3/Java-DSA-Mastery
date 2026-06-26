# 🎯 Interview Questions

---

# Beginner Level

### Q1. What is Time Complexity?

Answer:

Time Complexity measures how the execution time of an algorithm grows as the input size increases.

---

### Q2. What is Space Complexity?

Answer:

Space Complexity measures the amount of memory used by an algorithm during execution.

---

### Q3. What is Big-O Notation?

Answer:

Big-O represents the upper bound (worst-case) time complexity of an algorithm.

---

### Q4. Difference between Big-O, Big-Ω and Big-Θ?

| Notation | Meaning |
|----------|---------|
| Big-O | Worst Case |
| Big-Ω | Best Case |
| Big-Θ | Average / Tight Bound |

---

### Q5. Why do we ignore constants?

Example

```
O(5n)

↓

O(n)
```

Because constants become insignificant for very large inputs.

---

# Intermediate Level

### Q6. Difference between Time Complexity and Actual Running Time?

Answer:

Actual running time depends on CPU, RAM, compiler and operating system.

Time Complexity depends only on the algorithm.

---

### Q7. What is Auxiliary Space?

Answer:

Extra memory used by an algorithm excluding input memory.

---

### Q8. Why is Binary Search O(log n)?

Because each iteration reduces the search space by half.

---

### Q9. Why is Merge Sort O(n log n)?

Because there are log n levels and each level processes n elements.

---

### Q10. What is Amortized Complexity?

Average complexity over a sequence of operations.

Example:

ArrayList.add()

Amortized

```
O(1)
```

---

# Google Interview Questions

1. Can you optimize O(n²) to O(n)?
2. Which complexity matters more, Time or Space?
3. Why is HashMap average O(1)?
4. Explain recursion stack complexity.
5. Why is Quick Sort worst case O(n²)?
6. Difference between iterative and recursive Binary Search?
7. How do you analyze nested loops?
8. Explain Big-O without using mathematical notation.
9. Can two algorithms have the same Time Complexity but different performance?
10. How do you prove your solution is optimal?

---

# Interview Tip

Whenever you answer complexity questions,

Always justify your answer.

Don't simply say

```
O(n)
```

Explain why.