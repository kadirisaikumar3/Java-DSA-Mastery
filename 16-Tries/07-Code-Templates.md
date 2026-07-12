# ☕ Java Code Templates

---

# Trie Node

```java
class TrieNode {

    TrieNode[] children = new TrieNode[26];

    boolean isEnd;

}
```

---

# Insert

```java
void insert(String word){

    TrieNode current = root;

    for(char ch : word.toCharArray()){

        int index = ch - 'a';

        if(current.children[index] == null)

            current.children[index] = new TrieNode();

        current = current.children[index];

    }

    current.isEnd = true;

}
```

---

# Search

```java
boolean search(String word){

    TrieNode current = root;

    for(char ch : word.toCharArray()){

        int index = ch - 'a';

        if(current.children[index] == null)

            return false;

        current = current.children[index];

    }

    return current.isEnd;

}
```

---

# StartsWith

```java
boolean startsWith(String prefix){

    TrieNode current = root;

    for(char ch : prefix.toCharArray()){

        int index = ch - 'a';

        if(current.children[index] == null)

            return false;

        current = current.children[index];

    }

    return true;

}
```

---

# Interview Tip

Master these three methods:

- Insert
- Search
- StartsWith

Most Trie interview questions build upon them.