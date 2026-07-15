# ☕ Java Code Templates

---

# Memoization

```java
int solve(int n){

    if(n <= 1)

        return n;

    if(dp[n] != -1)

        return dp[n];

    return dp[n] =
        solve(n-1) + solve(n-2);

}
```

---

# Tabulation

```java
dp[0] = 0;

dp[1] = 1;

for(int i = 2; i <= n; i++){

    dp[i] = dp[i-1] + dp[i-2];

}
```

---

# Space Optimization

```java
int prev2 = 0;

int prev1 = 1;

for(int i = 2; i <= n; i++){

    int curr = prev1 + prev2;

    prev2 = prev1;

    prev1 = curr;

}
```

---

# Interview Tip

Many DP problems can reduce

```
O(n)

↓

O(1)
```

space by storing only the required previous states.