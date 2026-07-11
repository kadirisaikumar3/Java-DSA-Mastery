# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Use the BST property while searching.

```
Target < Root

↓

Go Left

Target > Root

↓

Go Right
```

---

# Example

```
        8
       / \
      3   10
```

Search

```
Target = 10

8

↓

Go Right

↓

Found
```

---

# Complexity

Balanced BST

```
Search

O(log n)
```

Worst Case

```
O(n)
```

---

# Advantages

- Faster Search
- Faster Insert
- Faster Delete

---

# Interview Tip

Every comparison removes nearly half of the remaining search space in a balanced BST.