# 🎯 Interview Questions

---

# Beginner

### 1. What is Union Find?

Union Find (Disjoint Set Union - DSU) is a data structure used to efficiently maintain disjoint sets and answer connectivity queries.

---

### 2. What are the two main operations?

- Find
- Union

---

### 3. What does the Find operation do?

It returns the representative (root) of the set containing an element.

---

### 4. What does the Union operation do?

It merges two different sets into one.

---

### 5. Why is DSU useful?

It efficiently solves connectivity, cycle detection, and grouping problems.

---

# Intermediate

### 6. What is Path Compression?

It makes every visited node point directly to the root, reducing tree height.

---

### 7. What is Union by Rank?

It attaches the smaller-height tree under the taller tree.

---

### 8. What is Union by Size?

It attaches the smaller set under the larger set.

---

### 9. Why is DSU almost O(1)?

Because Path Compression and Union by Rank reduce operations to **O(α(n))**, where α is the Inverse Ackermann Function.

---

### 10. Where is DSU commonly used?

- Connected Components
- Cycle Detection
- Kruskal's MST
- Dynamic Connectivity
- Accounts Merge

---

# Google-Level Questions

- Number of Provinces
- Redundant Connection
- Accounts Merge
- Graph Valid Tree
- Number of Islands II
- Most Stones Removed
- Min Cost to Connect All Points

---

# Interview Tip

Always explain:

- Parent Array
- Find Operation
- Union Operation
- Optimizations
- Time & Space Complexity