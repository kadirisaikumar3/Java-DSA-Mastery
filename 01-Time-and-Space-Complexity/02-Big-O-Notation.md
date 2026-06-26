# 📈 Big-O Notation

---

# What is Big-O?

Big-O Notation describes the **upper bound** of an algorithm's running time.

It tells us the maximum amount of work an algorithm performs as the input size grows.

Big-O focuses on **growth rate**, not the exact running time.

---

# Why Big-O?

Suppose two algorithms solve the same problem.

Algorithm A

```
10n + 20
```

Algorithm B

```
2n² + 5
```

For small values of n, both may seem fast.

As n increases:

```
10n + 20

↓

Linear Growth
```

```
2n² + 5

↓

Quadratic Growth
```

Algorithm A scales much better.

---

# Common Big-O Complexities

## O(1)

Constant Time

Example:

```
arr[5]
```

Accessing an array element.

---

## O(log n)

Logarithmic Time

Example:

Binary Search

Each step cuts the search space in half.

---

## O(n)

Linear Time

Example:

Linear Search

Traverse every element once.

---

## O(n log n)

Example:

- Merge Sort
- Heap Sort
- Quick Sort (Average Case)

---

## O(n²)

Example:

Bubble Sort

Nested loops.

---

## O(n³)

Triple nested loops.

---

## O(2ⁿ)

Exponential Time.

Example:

Recursive Fibonacci (without memoization).

---

## O(n!)

Factorial Time.

Example:

Generating all permutations.

---

# Complexity Comparison

```
Best

O(1)

↓

O(log n)

↓

O(n)

↓

O(n log n)

↓

O(n²)

↓

O(n³)

↓

O(2ⁿ)

↓

O(n!)

Worst
```

---

# Interview Example

Question:

Which is better?

```
O(n)

or

O(n log n)
```

Answer

```
O(n)
```

because it grows more slowly.

---

# Important Rules

Ignore Constants

```
O(5n)

↓

O(n)
```

Ignore Lower Order Terms

```
O(n² + n)

↓

O(n²)
```

---

# Interview Tip

Whenever an interviewer asks:

"What's the complexity?"

Always answer:

- Time Complexity
- Space Complexity

Never mention only one.