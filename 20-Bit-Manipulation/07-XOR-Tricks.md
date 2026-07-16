# 🎯 XOR Tricks

---

# Important Properties

```
a ^ a = 0
```

```
a ^ 0 = a
```

```
a ^ b ^ a = b
```

```
a ^ b = b ^ a
```

---

# Applications

- Single Number
- Missing Number
- Swap Numbers
- Find Unique Element

---

# Swap Without Temporary Variable

```java
a = a ^ b;

b = a ^ b;

a = a ^ b;
```

---

# Complexity

```
O(1)
```

---

# Interview Tip

Most Bit Manipulation interview questions revolve around XOR properties.