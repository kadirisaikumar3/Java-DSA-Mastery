# 🔄 Cycle Detection

---

# Idea

If two vertices already belong to the same set, adding an edge between them creates a cycle.

---

# Algorithm

For every edge (u, v):

1. Find the parent of u.
2. Find the parent of v.
3. If both parents are the same:

```
Cycle Found
```

Otherwise,

```
Union(u, v)
```

---

# Java Template

```java
for(int[] edge : edges){

    int u = edge[0];
    int v = edge[1];

    if(find(u) == find(v))
        return true;

    union(u, v);

}

return false;
```

---

# Complexity

```
O(E × α(n))
```

---

# Interview Tip

Union Find is the preferred approach for cycle detection in **undirected graphs**.