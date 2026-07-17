# 📋 Math for DSA Cheat Sheet

## GCD

```java
gcd(a, b) = gcd(b, a % b)
```

Complexity

```
O(log n)
```

---

## LCM

```java
LCM = (a / gcd(a, b)) * b
```

---

## Prime Check

Check divisibility only up to

```
√n
```

Complexity

```
O(√n)
```

---

## Sieve of Eratosthenes

Complexity

```
O(n log log n)
```

---

## Fast Exponentiation

Complexity

```
O(log n)
```

---

## Modular Arithmetic

```text
(a + b) % m

(a - b) % m

(a × b) % m
```

---

## Common Modulus

```text
1,000,000,007
```

---

## Pattern Recognition

Divisibility?

↓

GCD / LCM

Prime Queries?

↓

Sieve

Large Powers?

↓

Binary Exponentiation

Large Numbers?

↓

Modular Arithmetic

---

## Golden Rule

Look for **mathematical observations** before writing code.