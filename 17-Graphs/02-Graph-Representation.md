# 📊 Graph Representation

---

# 1. Adjacency Matrix

```
    A B C

A   0 1 1

B   1 0 0

C   1 0 0
```

Space

```
O(V²)
```

---

# 2. Adjacency List

```
A → B → C

B → A

C → A
```

Space

```
O(V + E)
```

---

# Java Representation

```java
List<List<Integer>> graph = new ArrayList<>();

for(int i = 0; i < n; i++){

    graph.add(new ArrayList<>());

}
```

---

# Comparison

| Representation | Space |
|---------------|-------|
| Matrix | O(V²) |
| List | O(V + E) |

---

# Interview Tip

Adjacency Lists are preferred in coding interviews because they are memory-efficient for sparse graphs.