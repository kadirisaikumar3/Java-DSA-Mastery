# 📖 Hashing Concepts

---

# What is Hashing?

Hashing is the process of mapping data to a fixed-size value called a hash code.

The hash code determines where the data will be stored.

---

# Example

```
Key

101

↓

Hash Function

↓

Bucket 5
```

---

# Components

- Key
- Value
- Hash Function
- Bucket
- Hash Table

---

# Why Hashing?

Without Hashing

```
Search

O(n)
```

With Hashing

```
Average

O(1)
```

---

# Advantages

- Fast Search
- Fast Insert
- Fast Delete
- Efficient Lookup

---

# Disadvantages

- Collisions
- Extra Memory
- Worst Case O(n)

---

# Time Complexity

| Operation | Average | Worst |
|-----------|----------|--------|
| Search | O(1) | O(n) |
| Insert | O(1) | O(n) |
| Delete | O(1) | O(n) |

---

# Interview Tip

Whenever you hear

- Frequency
- Duplicate
- Lookup

Think:

```
HashMap

or

HashSet
```