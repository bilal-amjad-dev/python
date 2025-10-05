

### Break Example (Stop the loop)

```bash
fruits = ["apple", "banana", "cherry", "mango"]

for fruit in fruits:
    if fruit == "cherry":
        break  # Stop the loop here
    print(fruit)
```

**Output:**

```bash
apple
banana
```
**Explanation:** When it finds "cherry", it **stops** the entire loop.

---

### Continue Example (Skip to next)

```bash
fruits = ["apple", "banana", "cherry", "mango"]

for fruit in fruits:
    if fruit == "cherry":
        continue  # Skip cherry
    print(fruit)
```

**Output:**

```bash
apple
banana
mango
```

**Explanation:** When it finds "cherry", it **skips** it and continues with the rest.


---


### Practice Exercise - Automating Log File Analysis

**Introduction**

In this practice exercise, we use a "for" loop to automate the analysis of a log file and identify lines containing the word "error." This demonstrates how loops can be used to process data and extract relevant information efficiently.

**Example:**

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


**Output:**

```bash
ERROR: File not found
ERROR: Database connection failed
```
In this exercise, the loop iterates through the "log_file" list and prints lines containing the word "ERROR."







