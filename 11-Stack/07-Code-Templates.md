# ☕ Java Code Templates

---

# Basic Stack

```java
Stack<Integer> stack = new Stack<>();

stack.push(10);
stack.push(20);
stack.push(30);

System.out.println(stack.peek());

stack.pop();
```

---

# Using Deque (Recommended)

```java
Deque<Integer> stack = new ArrayDeque<>();

stack.push(10);
stack.push(20);

System.out.println(stack.peek());

stack.pop();
```

---

# Monotonic Increasing Stack

```java
Stack<Integer> stack = new Stack<>();

for(int num : nums){

    while(!stack.isEmpty() && stack.peek() > num){

        stack.pop();

    }

    stack.push(num);

}
```

---

# Next Greater Element Template

```java
Stack<Integer> stack = new Stack<>();

for(int i = nums.length - 1; i >= 0; i--){

    while(!stack.isEmpty() && stack.peek() <= nums[i]){

        stack.pop();

    }

    answer[i] = stack.isEmpty() ? -1 : stack.peek();

    stack.push(nums[i]);

}
```

---

# Interview Tip

For production-quality Java code, prefer `ArrayDeque` over `Stack` for implementing stack behavior unless the problem specifically requires `Stack`.