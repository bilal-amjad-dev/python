

### Break Example (Stop the loop)

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

When it finds "cherry", it **stops** the entire loop.

---

### Continue Example (Skip to next)

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

When it finds "cherry", it **skips** it and continues with the rest.

---


### Practice Exercise - Automating Log File Analysis

```bash
log_file = [
   "INFO: Operation successful",
   "ERROR: File not found",
   "DEBUG: Connection established",
   "ERROR: Database connection failed",
]

for line in log_file:
   if "ERROR" in line:
       print(line)
```


Output:

```bash
ERROR: File not found
ERROR: Database connection failed
```







