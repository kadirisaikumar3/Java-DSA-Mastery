# 🤝 Union Operation

---

# Purpose

The Union operation merges two different sets into one.

---

# Java Template

```java
void union(int x, int y){

    int rootX = find(x);

    int rootY = find(y);

    if(rootX != rootY){

        parent[rootY] = rootX;

    }

}
```

---

# Example

Initially

```
1     2
```

After

```
union(1,2)
```

```
1

|

2
```

---

# Complexity

Without optimization

```
O(n)
```

With Rank & Path Compression

```
Almost O(1)
```

---

# Interview Tip

Always perform **Find()** before Union() to avoid merging incorrect nodes.