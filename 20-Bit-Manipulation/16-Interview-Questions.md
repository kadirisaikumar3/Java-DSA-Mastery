# 🎯 Interview Questions

---

# Beginner

### 1. What is Bit Manipulation?

Bit Manipulation is the technique of performing operations directly on the binary representation of numbers.

---

### 2. What are the main bitwise operators?

- AND (&)
- OR (|)
- XOR (^)
- NOT (~)
- Left Shift (<<)
- Right Shift (>>)

---

### 3. How do you check if a number is a power of two?

```java
(n > 0) && ((n & (n - 1)) == 0)
```

---

### 4. What is XOR?

XOR returns `1` if two bits are different; otherwise, it returns `0`.

---

### 5. How do you count set bits efficiently?

Use Brian Kernighan's Algorithm:

```java
while(n != 0){
    n = n & (n - 1);
    count++;
}
```

---

# Intermediate

### 6. What is Bit Masking?

Bit Masking manipulates individual bits using bitwise operators.

---

### 7. Why does `n & (n - 1)` work?

It removes the lowest set bit from a number.

---

### 8. Why is XOR used in the Single Number problem?

Duplicate numbers cancel each other because:

```text
a ^ a = 0
0 ^ b = b
```

---

### 9. How are subsets generated using bits?

Each bit in a mask represents whether an element is included or excluded.

---

### 10. When should Bit Manipulation be used?

When problems involve binary representation, flags, powers of two, unique elements, or subsets.

---

# Google-Level Questions

- Single Number
- Missing Number
- Counting Bits
- Maximum XOR of Two Numbers
- Subsets
- Single Number III

---

# Interview Tip

Always explain:

- Binary representation
- Chosen bit operation
- Time & Space Complexity