# ➗ Modular Arithmetic

---

# What is Modular Arithmetic?

Modular arithmetic works with the remainder after division.

```
a % m
```

---

# Properties

Addition

```
(a + b) % m

=

((a % m) + (b % m)) % m
```

---

Subtraction

```
(a - b) % m

=

((a % m) - (b % m) + m) % m
```

---

Multiplication

```
(a × b) % m

=

((a % m) × (b % m)) % m
```

---

# Common Modulus

```text
1,000,000,007
```

A large prime commonly used to prevent integer overflow.

---

# Applications

- Dynamic Programming
- Large Number Calculations
- Cryptography
- Competitive Programming

---

# Interview Tip

Apply the modulus during calculations instead of only at the end to avoid overflow.