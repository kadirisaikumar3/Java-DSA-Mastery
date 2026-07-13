# 🔄 BFS and DFS

---

# Breadth First Search (BFS)

Visits nodes level by level.

Uses

```
Queue
```

Applications

- Shortest Path (Unweighted Graph)
- Level Traversal
- Connected Components

---

# Depth First Search (DFS)

Explores one path completely before backtracking.

Uses

```
Recursion

or

Stack
```

Applications

- Cycle Detection
- Connected Components
- Topological Sort
- Backtracking

---

# Complexity

| Algorithm | Time |
|-----------|------|
| BFS | O(V + E) |
| DFS | O(V + E) |

---

# Java BFS

```java
Queue<Integer> queue = new LinkedList<>();
```

---

# Java DFS

```java
void dfs(int node){

    visited[node] = true;

}
```

---

# Interview Tip

Need the shortest path in an **unweighted** graph?

↓

Think **BFS**

Need complete exploration or recursion?

↓

Think **DFS**