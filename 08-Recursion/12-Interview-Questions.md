# 🎯 Interview Questions

---

# Beginner

### 1. What is Recursion?

A programming technique where a function calls itself to solve a smaller version of the same problem.

---

### 2. What are the two essential parts of recursion?

- Base Case
- Recursive Case

---

### 3. Why is the Base Case important?

It stops the recursion and prevents infinite recursive calls.

---

### 4. What happens if there is no Base Case?

The program keeps calling itself until a **StackOverflowError** occurs.

---

### 5. What is the Call Stack?

A memory structure that stores active function calls during program execution.

---

# Intermediate

### 6. What is Tail Recursion?

A recursive function where the recursive call is the final operation performed.

---

### 7. Does Java optimize Tail Recursion?

No.

Java does not support Tail Call Optimization (TCO).

---

### 8. What is the Time Complexity of Fibonacci using naive recursion?

```
O(2ⁿ)
```

---

### 9. How can recursive solutions be optimized?

Using:

- Memoization
- Dynamic Programming
- Iterative approaches (where applicable)

---

### 10. When should recursion be preferred?

- Trees
- Graph DFS
- Backtracking
- Divide & Conquer
- Dynamic Programming

---

# Google-Level Questions

- Generate Parentheses
- Subsets
- Permutations
- Tower of Hanoi
- Word Search
- Letter Combinations
- Recursive Binary Search

---

# Interview Tip

Always explain:

- Base Case
- Recursive Relation
- Call Stack
- Time Complexity
- Space Complexity