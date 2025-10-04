### Example 1

```bash
import sys

name = sys.argv[1]
print("Hello " + name)
```
Run
```bash
python hello.py John
```
Output
```bash
Hello John
```

---

### Example 2

```bash
import sys

number1 = int(sys.argv[1])
number2 = int(sys.argv[2])   # when we don't use int() , it will understand it string.

result = number1 + number2
print(result)
```

Run:
```bash
python calc.py 5 3
```

Output:
```bash
8
```
