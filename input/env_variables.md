
It's a variable stored in your computer's system (not in your code). Your program can read it.

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

Step 3: Run it:
```bash
python test.py
```

Output:
```bash
John
```
