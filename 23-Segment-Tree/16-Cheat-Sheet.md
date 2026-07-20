# 📋 Segment Tree Cheat Sheet

## Core Operations

Build

```java
build(node, start, end);
```

Query

```java
query(node, start, end, left, right);
```

Update

```java
update(node, start, end, index, value);
```

---

## Time Complexity

| Operation | Complexity |
|-----------|------------|
| Build | O(n) |
| Query | O(log n) |
| Point Update | O(log n) |
| Range Update (Lazy) | O(log n) |
| Space | O(4n) |

---

## Applications

- Range Sum Query
- Range Minimum Query
- Dynamic Updates
- Interval Problems
- Competitive Programming

---

## Pattern Recognition

Multiple Range Queries?

↓

Segment Tree

Range Updates?

↓

Lazy Propagation

Dynamic Array?

↓

Segment Tree

---

## Golden Rule

Segment Trees are preferred when both **queries** and **updates** must be efficient.