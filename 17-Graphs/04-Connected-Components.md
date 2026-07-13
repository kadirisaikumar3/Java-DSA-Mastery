# 🌍 Connected Components

---

# What are Connected Components?

A Connected Component is a group of vertices where every vertex is reachable from every other vertex.

---

# Example

```
Component 1

1 --- 2

|

3


Component 2

4 --- 5
```

Number of Connected Components = 2

---

# Algorithm

1. Traverse every node.
2. If not visited:
   - Start BFS/DFS.
   - Mark all reachable nodes.
3. Increase component count.

---

# Complexity

Time

```
O(V + E)
```

Space

```
O(V)
```

---

# Applications

- Number of Provinces
- Number of Islands
- Network Connectivity

---

# Interview Tip

If the problem asks:

"How many separate groups?"

↓

Think **Connected Components**.