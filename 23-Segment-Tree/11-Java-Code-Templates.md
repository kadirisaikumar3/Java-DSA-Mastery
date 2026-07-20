# ☕ Java Code Templates

---

# Build

```java
build(node, start, end);
```

---

# Query

```java
query(node, start, end, left, right);
```

---

# Update

```java
update(node, start, end, index, value);
```

---

# Arrays

```java
int[] arr = new int[n];
int[] tree = new int[4 * n];
int[] lazy = new int[4 * n];
```

---

# Time Complexity

| Operation | Complexity |
|-----------|------------|
| Build | O(n) |
| Query | O(log n) |
| Update | O(log n) |

---

# Interview Tip

Allocate the Segment Tree array with size **4 × n** to safely accommodate all nodes.