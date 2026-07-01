# 🏷 HashSet

---

# What is HashSet?

HashSet stores only unique values.

Duplicate elements are automatically ignored.

---

# Declaration

```java
HashSet<Integer> set = new HashSet<>();
```

---

# Insert

```java
set.add(10);
```

---

# Search

```java
set.contains(10);
```

---

# Remove

```java
set.remove(10);
```

---

# Iterate

```java
for(int num : set){

    System.out.println(num);

}
```

---

# Complexity

| Operation | Time |
|-----------|------|
| add() | O(1) |
| contains() | O(1) |
| remove() | O(1) |

---

# Applications

- Duplicate Detection
- Visited Arrays
- Graph Traversal
- Unique Elements

---

# HashSet vs HashMap

| HashSet | HashMap |
|----------|----------|
| Stores Values | Stores Key-Value |
| Unique Values | Unique Keys |
| No Value | Key → Value |

---

# Interview Tip

Need only uniqueness?

Choose **HashSet**.

Need mapping?

Choose **HashMap**.