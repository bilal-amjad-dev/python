

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

