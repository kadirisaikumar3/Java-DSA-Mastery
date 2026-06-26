# ⏱️ Time Complexity

---

# What is Time Complexity?

Time Complexity measures how the number of operations performed by an algorithm grows as the input size (n) increases.

It is **not** the actual execution time in seconds.

Instead, it estimates the growth rate of an algorithm.

---

# Why is Time Complexity Important?

Efficient algorithms:

- Execute faster
- Handle larger inputs
- Scale better
- Improve user experience
- Reduce server costs

---

# Best Case

Minimum number of operations.

Example:

Linear Search

Target found at the first index.

```
O(1)
```

---

# Average Case

Expected number of operations over all possible inputs.

---

# Worst Case

Maximum number of operations.

Example:

Linear Search

Target found at the last index.

```
O(n)
```

Most interviewers ask for the **worst-case time complexity**.

---

# Common Time Complexities

## Constant Time

```
O(1)
```

Example:

```
arr[0]
```

---

## Logarithmic Time

```
O(log n)
```

Example:

Binary Search.

---

## Linear Time

```
O(n)
```

Example:

Linear Search.

---

## Linearithmic Time

```
O(n log n)
```

Example:

Merge Sort

Heap Sort

---

## Quadratic Time

```
O(n²)
```

Example:

Bubble Sort

Nested Loops

---

## Cubic Time

```
O(n³)
```

Triple Nested Loops.

---

## Exponential Time

```
O(2ⁿ)
```

Example:

Recursive Fibonacci.

---

## Factorial Time

```
O(n!)
```

Example:

Generating all permutations.

---

# Rules for Calculating Time Complexity

## Ignore Constants

```
O(5n)

↓

O(n)
```

---

## Ignore Lower Order Terms

```
O(n² + n)

↓

O(n²)
```

---

## Consecutive Loops

```
for(...)
for(...)
```

Complexity

```
O(n) + O(n)

↓

O(n)
```

---

## Nested Loops

```
for(...)
    for(...)
```

Complexity

```
O(n²)
```

---

# Interview Tip

Always conclude your solution with:

- Time Complexity
- Why it is optimal
- Whether further optimization is possible

This demonstrates a complete understanding of the algorithm.

---

# Summary

Time Complexity helps compare algorithms based on their scalability rather than actual execution time, enabling developers to choose the most efficient solution for large datasets.