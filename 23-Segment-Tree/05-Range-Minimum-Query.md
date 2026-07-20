# 📉 Range Minimum Query (RMQ)

---

# Purpose

Find the minimum value within a specified range.

---

# Example

Array

```
[7, 2, 9, 1, 5]
```

Query

```
Min(1,4)
```

Result

```
1
```

---

# Difference from Sum Query

Instead of storing sums,

Each node stores

```
Minimum Value
```

---

# Merge Function

```java
tree[node] = Math.min(tree[left], tree[right]);
```

---

# Complexity

```
O(log n)
```

---

# Interview Tip

The tree structure remains the same. Only the merge operation changes depending on the problem.