# ☕ Java Code Templates

---

# Find

```java
int find(int x){

    if(parent[x] != x)
        parent[x] = find(parent[x]);

    return parent[x];

}
```

---

# Union by Rank

```java
void union(int x, int y){

    int rx = find(x);
    int ry = find(y);

    if(rx == ry) return;

    if(rank[rx] < rank[ry])
        parent[rx] = ry;

    else if(rank[rx] > rank[ry])
        parent[ry] = rx;

    else{

        parent[ry] = rx;

        rank[rx]++;

    }

}
```

---

# Complexity

```
Almost O(1)
```