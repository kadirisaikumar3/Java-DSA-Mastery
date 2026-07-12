# ⚙️ Insert, Search & StartsWith

---

# Insert

Traverse character by character.

Create nodes if they do not exist.

Mark the last node as the end of the word.

---

# Search

Traverse each character.

If any character is missing

```
Return false
```

Otherwise

Return whether the last node is marked as the end of a word.

---

# StartsWith

Similar to Search.

Difference

The last node does not need to be the end of a word.

Only the prefix needs to exist.

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(L) |
| Search | O(L) |
| StartsWith | O(L) |

---

# Example

Insert

```
apple
```

Search

```
apple

→ true
```

StartsWith

```
app

→ true
```

Search

```
app

→ false
```

(if "app" was never inserted)

---

# Interview Tip

Search checks **complete words**.

StartsWith checks **prefixes only**.