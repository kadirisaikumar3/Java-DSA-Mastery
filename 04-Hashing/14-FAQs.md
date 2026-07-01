# ❓ Frequently Asked Questions

---

## Q1. Why is HashMap so fast?

Because it provides average-case O(1) lookup using hashing.

---

## Q2. What is a Collision?

Two keys mapping to the same bucket.

---

## Q3. Does HashMap maintain insertion order?

No.

Use LinkedHashMap if insertion order is required.

---

## Q4. Can HashMap store null values?

Yes.

- One null key
- Multiple null values

---

## Q5. Difference between HashMap and Hashtable?

| HashMap | Hashtable |
|----------|------------|
| Not Synchronized | Synchronized |
| Faster | Slower |
| Allows null | Doesn't allow null |

---

## Q6. When should I use HashSet?

When only unique values are needed.

---

## Q7. What is Rehashing?

Increasing the bucket size and redistributing entries when the load factor exceeds the threshold.