# 🔄 State Transition

---

# What is a State?

A state represents the answer to a smaller subproblem.

---

# State Transition

A formula used to compute the current state from previous states.

---

# Example

Fibonacci

```
dp[i] = dp[i-1] + dp[i-2]
```

---

# Example

House Robber

```
dp[i] = max(

dp[i-1],

dp[i-2] + nums[i]

)
```

---

# DP Solving Steps

1. Define the State
2. Find the Transition
3. Define Base Cases
4. Fill DP Table
5. Return Final Answer

---

# Interview Tip

The hardest part of DP is defining the **state** correctly.

Once the state is clear, the transition usually follows naturally.