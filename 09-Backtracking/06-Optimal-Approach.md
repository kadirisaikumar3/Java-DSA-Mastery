# 🚀 Optimal Approach

---

# What is the Optimal Approach?

The optimal Backtracking solution combines recursion with pruning to avoid unnecessary work.

---

# General Algorithm

1. Make a Choice
2. Check Constraints
3. Recurse
4. Undo the Choice
5. Try Next Choice

---

# Java Template

```java
void backtrack(){

    if(baseCase){

        return;

    }

    for(each choice){

        makeChoice();

        backtrack();

        undoChoice();

    }

}
```

---

# Complexity

Worst Case

```
O(2ⁿ)

or

O(n!)
```

Pruning significantly reduces the actual running time.

---

# Advantages

- Efficient search
- Avoids invalid paths
- Generates all valid solutions

---

# Interview Tip

Explain how pruning reduces unnecessary recursive calls.