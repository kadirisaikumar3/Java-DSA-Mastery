# ❌ Common Mistakes

---

## Mistake 1

Using `==` to compare Strings.

❌ Wrong

```java
str1 == str2
```

✅ Correct

```java
str1.equals(str2)
```

---

## Mistake 2

Ignoring String Immutability.

Every modification creates a new object.

---

## Mistake 3

Using String concatenation inside loops.

❌

```java
str += ch;
```

✅

```java
StringBuilder sb = new StringBuilder();
```

---

## Mistake 4

Forgetting Edge Cases

- Empty String
- Single Character
- Spaces
- Uppercase & Lowercase
- Unicode Characters

---

## Mistake 5

Ignoring Time Complexity

Repeated concatenation may become

```
O(n²)
```

---

## Interview Advice

Prefer `StringBuilder` when repeatedly modifying strings.