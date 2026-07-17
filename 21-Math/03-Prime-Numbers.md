# 🔷 Prime Numbers

---

# What is a Prime Number?

A prime number has exactly two positive divisors:

- 1
- Itself

---

# Examples

```
2

3

5

7

11

13
```

---

# Check Prime

Iterate only up to

```
√n
```

---

# Complexity

```
O(√n)
```

---

# Java Template

```java
boolean isPrime(int n){

    if(n < 2)

        return false;

    for(int i = 2; i * i <= n; i++){

        if(n % i == 0)

            return false;

    }

    return true;

}
```

---

# Interview Tip

Checking divisibility up to **√n** is the optimal approach for primality testing.