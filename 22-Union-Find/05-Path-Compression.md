# ⚡ Path Compression

---

# What is Path Compression?

Path Compression flattens the tree whenever Find is called.

Every visited node directly points to the root.

---

# Java Template

```java
int find(int x){

    if(parent[x] != x){

        parent[x] = find(parent[x]);

    }

    return parent[x];

}
```

---

# Example

Before

```
4

↓

3

↓

2

↓

1
```

After

```
4

↓

1

3

↓

1

2

↓

1
```

---

# Advantages

- Faster Future Queries
- Smaller Tree Height
- Nearly Constant-Time Operations

---

# Interview Tip

Path Compression is the single biggest optimization in DSU.