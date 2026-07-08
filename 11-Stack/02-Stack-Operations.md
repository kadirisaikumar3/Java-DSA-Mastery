# ⚙️ Stack Operations

---

# Push

Adds an element to the top of the stack.

```

Before

10

20

↓

Push(30)

↓

10

20

30

```

---

# Pop

Removes the top element.

```

10

20

30

↓

Pop()

↓

10

20

```

---

# Peek

Returns the top element without removing it.

---

# isEmpty()

Returns true if the stack has no elements.

---

# Java Example

```java
Stack<Integer> stack = new Stack<>();

stack.push(10);
stack.push(20);
stack.push(30);

System.out.println(stack.peek());

stack.pop();
```

---

# Complexity

| Operation | Complexity |
|-----------|------------|
| Push | O(1) |
| Pop | O(1) |
| Peek | O(1) |

---

# Interview Tip

Always check whether the stack is empty before calling pop() or peek().