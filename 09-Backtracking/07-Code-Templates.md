# ☕ Java Code Templates

---

# Basic Backtracking

```java
void backtrack(){

    if(baseCase){

        result.add(new ArrayList<>(path));

        return;

    }

    for(int i = start; i < n; i++){

        path.add(nums[i]);

        backtrack();

        path.remove(path.size()-1);

    }

}
```

---

# Subsets Template

```java
void dfs(int index){

    result.add(new ArrayList<>(path));

    for(int i = index; i < nums.length; i++){

        path.add(nums[i]);

        dfs(i + 1);

        path.remove(path.size() - 1);

    }

}
```

---

# Permutations Template

```java
void dfs(){

    if(path.size() == nums.length){

        result.add(new ArrayList<>(path));

        return;

    }

    for(int i = 0; i < nums.length; i++){

        if(used[i])

            continue;

        used[i] = true;

        path.add(nums[i]);

        dfs();

        path.remove(path.size()-1);

        used[i] = false;

    }

}
```

---

# Combination Sum Template

```java
path.add(nums[i]);

dfs(i);

path.remove(path.size()-1);
```

---

# Interview Tip

Every Backtracking template follows the same pattern:

```
Choose

↓

Explore

↓

Undo
```