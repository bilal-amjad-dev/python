

### 🧠 **Definition of `try` and `except`**

- **`try` block**: This is where you write code that **might cause an error**. Python will attempt to run this code.
- **`except` block**: If an error occurs in the `try` block, Python will **jump to the `except` block** and run that code instead of crashing.

---




```bash
number = int(input("Enter a number: "))
print("You entered:", number)
```

Output:
```bash
python main.py
Enter a number: 1
You entered: 1
```

```bash
python main.py
Enter a number: a
Traceback (most recent call last):
  File "C:\Users\pc\Desktop\python\main.py", line 2, in <module>
    number = int(input("Enter a number: "))
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
ValueError: invalid literal for int() with base 10: 'a'
PS C:\Users\pc\Desktop\python> 
```

---















```bash
try:
    number = int(input("Enter a number: "))
    print("You entered:", number)
except ValueError:
    print("Oops! That wasn't a valid number.")
```



```bash
PS C:\Users\pc\Desktop\python> python .\main.py
Enter a number: 1
You entered: 1
```

```bash
PS C:\Users\pc\Desktop\python> python .\main.py
Enter a number: a
Oops! That wasn't a valid number.
```







