# ☕ Java Code Templates

---

# Traverse Linked List

```java
Node current = head;

while(current != null){

    System.out.print(current.data + " ");

    current = current.next;

}
```

---

# Reverse Linked List

```java
Node prev = null;
Node current = head;

while(current != null){

    Node next = current.next;

    current.next = prev;

    prev = current;

    current = next;

}

head = prev;
```

---

# Find Middle Node

```java
Node slow = head;
Node fast = head;

while(fast != null && fast.next != null){

    slow = slow.next;
    fast = fast.next.next;

}

return slow;
```

---

# Detect Cycle

```java
Node slow = head;
Node fast = head;

while(fast != null && fast.next != null){

    slow = slow.next;
    fast = fast.next.next;

    if(slow == fast)
        return true;

}

return false;
```

---

# Dummy Node Template

```java
Node dummy = new Node(-1);

dummy.next = head;
```

---

# Interview Tip

Master these templates—they appear repeatedly in Linked List interview questions.