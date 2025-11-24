A **primary constructor** is a new C# 12 feature that lets you put constructor parameters directly on the class itself instead of writing a full constructor block.

```CS
// Old Style
class User {
    public string Name { get; set; }
    
    public User(string name) {
        Name = name;
    }
}

// Primary constructor (new style):
class User(string name) {
    public string Name { get; set; } = name;
}
```

**Why is this useful?**

- Because it removes a lot of boilerplate.  
- You no longer need to write a constructor body unless you need extra logic.

