# ❌ Common Mistakes

---

## Mistake 1

Confusing Time Complexity with Execution Time.

Execution time depends on hardware.

Complexity depends on the algorithm.

---

## Mistake 2

Ignoring recursion stack.

Recursive functions consume stack memory.

---

## Mistake 3

Including constants.

Wrong

```
O(5n)
```

Correct

```
O(n)
```

---

## Mistake 4

Adding nested loops.

Wrong

```
O(n+n)

for nested loops
```

Correct

```
O(n²)
```

---

## Mistake 5

Ignoring Space Complexity.

Interviewers expect both.

---

## Mistake 6

Thinking Binary Search works on unsorted arrays.

It requires sorted data.

---

## Mistake 7

Believing Worst Case always happens.

Worst Case is a guarantee, not a certainty.

---

## Interview Advice

After solving every problem ask yourself:

- Can Time be improved?
- Can Space be improved?
- Is this optimal?