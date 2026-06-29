# 📖 Array Concepts

---

# What is an Array?

An array is a linear data structure that stores elements of the same data type in contiguous memory locations.

Each element can be accessed using an index.

Example:

```
Index

0 1 2 3 4

Array

10 20 30 40 50
```

---

# Characteristics

- Fixed Size
- Contiguous Memory
- Random Access
- Same Data Type
- Zero-Based Indexing (Java)

---

# Memory Representation

```
Address

100
104
108
112
116
```

Values

```
10

20

30

40

50
```

Each integer occupies 4 bytes.

---

# Declaration

```java
int[] arr = new int[5];
```

---

# Initialization

```java
int[] arr = {10,20,30,40,50};
```

---

# Accessing Elements

```java
System.out.println(arr[2]);
```

Output

```
30
```

---

# Advantages

- Constant Time Access
- Easy Traversal
- Cache Friendly
- Simple Implementation

---

# Disadvantages

- Fixed Size
- Costly Insertions
- Costly Deletions

---

# Time Complexity

| Operation | Complexity |
|-----------|------------|
| Access | O(1) |
| Search | O(n) |
| Insert | O(n) |
| Delete | O(n) |
| Traverse | O(n) |

---

# Interview Tip

Arrays are the most frequently tested topic in coding interviews.

Master arrays before moving to advanced data structures.