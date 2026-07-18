# 🔍 Find Operation

---

# Purpose

The Find operation returns the representative (root) of the set containing a node.

---

# Java Template

```java
int find(int x){

    if(parent[x] == x)

        return x;

    return find(parent[x]);

}
```

---

# Example

Parent Array

```
0 0 0 3 3
```

```
find(2)

↓

0
```

```
find(4)

↓

3
```

---

# Complexity

Without optimization

```
O(n)
```

With Path Compression

```
Almost O(1)
```

---

# Interview Tip

The Find operation becomes extremely efficient when combined with **Path Compression**.