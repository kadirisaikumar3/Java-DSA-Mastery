# ☕ Java Code Templates

---

# GCD

```java
int gcd(int a, int b){

    while(b != 0){

        int temp = b;
        b = a % b;
        a = temp;

    }

    return a;

}
```

---

# LCM

```java
int lcm(int a, int b){

    return (a / gcd(a, b)) * b;

}
```

---

# Prime Check

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

# Fast Power

```java
long power(long a, long b){

    long result = 1;

    while(b > 0){

        if((b & 1) == 1)
            result *= a;

        a *= a;
        b >>= 1;

    }

    return result;

}
```

---

# Interview Tip

These templates solve a large percentage of Math-based interview problems.