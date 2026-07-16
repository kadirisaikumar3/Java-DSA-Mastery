# 🎭 Bit Masking

---

# What is Bit Masking?

Bit Masking uses bitwise operations to manipulate specific bits.

---

# Common Operations

Set Bit

```java
n | (1 << i)
```

---

Clear Bit

```java
n & ~(1 << i)
```

---

Toggle Bit

```java
n ^ (1 << i)
```

---

Check Bit

```java
(n & (1 << i)) != 0
```

---

# Applications

- Permission Systems
- State Compression
- Subset Enumeration
- Flags

---

# Interview Tip

Remember these four operations:

- Set
- Clear
- Toggle
- Check

These are the foundation of most Bit Manipulation problems.