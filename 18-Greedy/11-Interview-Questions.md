# 🎯 Interview Questions

---

# Beginner

### 1. What is a Greedy Algorithm?

A Greedy Algorithm makes the best local choice at every step, hoping to achieve the global optimum.

---

### 2. What are the two conditions required for Greedy?

- Greedy Choice Property
- Optimal Substructure

---

### 3. What is the Time Complexity of most Greedy algorithms?

Usually

```
O(n)

or

O(n log n)
```

---

### 4. Why is sorting used in Greedy problems?

Sorting helps process elements in the order that leads to the optimal local choice.

---

### 5. Does Greedy always give the optimal answer?

No.

Only if the problem satisfies the Greedy Choice Property and Optimal Substructure.

---

# Intermediate

### 6. What is the difference between Greedy and Dynamic Programming?

Greedy makes one best choice and never revisits it.

Dynamic Programming explores multiple possibilities and stores results.

---

### 7. Why is Activity Selection solved using Greedy?

Choosing the activity that finishes earliest leaves maximum time for future activities.

---

### 8. Why does Fractional Knapsack use Greedy?

Items are selected by the highest value-to-weight ratio, which guarantees the optimal solution.

---

### 9. What is the biggest limitation of Greedy?

It cannot solve every optimization problem.

---

### 10. When should Greedy be avoided?

When a locally optimal choice may prevent reaching the globally optimal solution.

---

# Google-Level Questions

- Jump Game
- Gas Station
- Candy
- Activity Selection
- Fractional Knapsack
- Huffman Coding
- IPO

---

# Interview Tip

Always explain:

- Why the Greedy choice is correct
- Why it never needs to be changed
- Time & Space Complexity