
```bash
import sys
type = sys.argv[1]
if type == "t2.micro":
 print("ok, we create ec2 for you")
```

```bash
import sys
type = sys.argv[1]
if type == "t2.micro":
 print("ok, we create ec2 for you")
else:
 print("your input is not t2.micro, so we cannot")
```

```bash
python test.py t2.micro
```

```bash
import sys
type = sys.argv[1]
if type == "t2.micro":
 print("you will be changed 2 dollars")

elif type == "t2.medium":
 print("it will change you 4 dollars")

elif type == "t2.xlarge":
 print("you will be changed 8 dollars")
else:
 print("your input is not t2.micro, so we cannot")
```
