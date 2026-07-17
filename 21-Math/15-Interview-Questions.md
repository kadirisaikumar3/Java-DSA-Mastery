# 🎯 Interview Questions

---

# Beginner

### 1. What is GCD?

The Greatest Common Divisor (GCD) is the largest number that divides two integers without leaving a remainder.

---

### 2. What is LCM?

The Least Common Multiple (LCM) is the smallest positive number divisible by both numbers.

---

### 3. What is the Euclidean Algorithm?

It efficiently computes the GCD using:

```java
gcd(a, b) = gcd(b, a % b)
```

---

### 4. How do you check whether a number is prime?

Check divisibility only up to **√n**.

---

### 5. What is the Sieve of Eratosthenes?

An efficient algorithm to find all prime numbers up to `n`.

---

# Intermediate

### 6. Why does the Sieve start marking from `i × i`?

Smaller multiples have already been marked by smaller prime numbers.

---

### 7. What is Modular Arithmetic?

Arithmetic performed using the remainder after division by a modulus.

---

### 8. What is Binary Exponentiation?

A technique to compute powers in **O(log n)** by repeatedly squaring the base.

---

### 9. Difference between Permutations and Combinations?

- Permutations → Order matters.
- Combinations → Order does not matter.

---

### 10. When should mathematical optimization be used?

When problems involve divisibility, prime numbers, powers, modular operations, or counting.

---

# Google-Level Questions

- Count Primes
- Pow(x, n)
- GCD of Strings
- Prime Palindrome
- Happy Number
- Nth Magical Number

---

# Interview Tip

Always explain:

- Mathematical observation
- Chosen algorithm
- Time & Space Complexity