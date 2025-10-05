

### `Break` Example (Stop the loop)

```bash
fruits = ["apple", "banana", "cherry", "mango"]

for fruit in fruits:
    if fruit == "cherry":
        break  # Stop the loop here
    print(fruit)
```

Output:
```bash
apple
banana
```
**Explanation:** When it finds "cherry", it **stops** the entire loop.


### `Continue` Example (Skip to next)

```bash
fruits = ["apple", "banana", "cherry", "mango"]

for fruit in fruits:
    if fruit == "cherry":
        continue  # Skip cherry
    print(fruit)
```

Output:

```bash
apple
banana
mango
```

**Explanation:** When it finds "cherry", it **skips** it and continues with the rest.

