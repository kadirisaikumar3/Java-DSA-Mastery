# 📦 Union by Size

---

# What is Size?

Each set stores the number of nodes it contains.

Always attach the smaller set to the larger set.

---

# Java Template

```java
if(size[rootX] < size[rootY]){

    parent[rootX] = rootY;

    size[rootY] += size[rootX];

}
else{

    parent[rootY] = rootX;

    size[rootX] += size[rootY];

}
```

---

# Advantages

- Keeps Trees Balanced
- Fast Union Operations
- Easy to Implement

---

# Rank vs Size

Rank

↓

Tree Height

Size

↓

Number of Nodes

---

# Interview Tip

Union by Size performs similarly to Union by Rank.