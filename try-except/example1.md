
```bash
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

try:
    div = num1 / num2
    print(div)
except ZeroDivisionError:
    print("You can't divide by zero!")
```

Output:

```bash
python main.py
Enter first number: 0
Enter second number: 5
0.0
```



```bash
python main.py
Enter first number: 5
Enter second number: 0
You can't divide by zero!
```


