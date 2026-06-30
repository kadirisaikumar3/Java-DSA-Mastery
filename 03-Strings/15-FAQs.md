# ❓ Frequently Asked Questions

---

## Q1. Why are Strings immutable?

For security, thread safety, and efficient memory usage through the String Pool.

---

## Q2. What is the String Pool?

A special memory area where identical String literals are stored only once.

---

## Q3. Difference between String and StringBuilder?

| String | StringBuilder |
|---------|---------------|
| Immutable | Mutable |
| Slower for modifications | Faster for modifications |

---

## Q4. Difference between StringBuilder and StringBuffer?

| StringBuilder | StringBuffer |
|---------------|--------------|
| Not Thread Safe | Thread Safe |
| Faster | Slower |

---

## Q5. When should I use StringBuilder?

When performing many string modifications or concatenations.

---

## Q6. Why use equals() instead of == ?

`==` compares references.

`equals()` compares content.

---

## Q7. Which String patterns are most important?

- Sliding Window
- Two Pointers
- Frequency Counting
- HashMap
- StringBuilder