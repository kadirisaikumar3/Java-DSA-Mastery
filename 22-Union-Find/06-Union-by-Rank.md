# 📊 Union by Rank

---

# What is Rank?

Rank approximates the height of the tree.

Always attach the smaller-ranked tree under the larger-ranked tree.

---

# Java Template

```java
if(rank[rootX] < rank[rootY]){

    parent[rootX] = rootY;

}
else if(rank[rootX] > rank[rootY]){

    parent[rootY] = rootX;

}
else{

    parent[rootY] = rootX;

    rank[rootX]++;

}
```

---

# Advantages

- Prevents Tall Trees
- Faster Find Operation
- Better Performance

---

# Complexity

Almost

```
O(1)
```

---

# Interview Tip

Rank represents tree height, **not** the number of nodes.