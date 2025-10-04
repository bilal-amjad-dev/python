

### Example 1

```bash
On Windows (Command Prompt):
$env:USERNAME = "John"

On Mac/Linux:
export USERNAME=John

```


```bash

import os

print(os.getenv("USERNAME"))
```

Run
```bash
python test.py
```

Output:
```bash
John
```
