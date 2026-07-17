# 🧮 Sieve of Eratosthenes

---

# What is the Sieve?

The Sieve of Eratosthenes is an efficient algorithm to find all prime numbers up to `n`.

---

# Idea

1. Assume every number is prime.
2. Start from 2.
3. Mark all multiples as non-prime.
4. Continue until √n.

---

# Java Template

```java
boolean[] prime = new boolean[n + 1];
Arrays.fill(prime, true);

prime[0] = false;
prime[1] = false;

for(int i = 2; i * i <= n; i++){

    if(prime[i]){

        for(int j = i * i; j <= n; j += i){

            prime[j] = false;

        }

    }

}
```

---

# Complexity

Time

```
O(n log log n)
```

Space

```
O(n)
```

---

# Applications

- Count Primes
- Prime Queries
- Competitive Programming

---

# Interview Tip

Always start marking multiples from `i * i` because smaller multiples are already processed.