| List | Tuple |
|------|-------|
| Lists are mutable | Tuples are immutable |
| Lists can be resized | Cannot be resized |
| `student_names = ["abi", "ram", "john", "tim"]`<br>`student_names.append("new_student")`<br>`print(student_names)`<br>**Output:** `['abi', 'ram', 'john', 'tim', 'new_student']` | `student_names = ("abi", "ram", "john", "tim")`<br>`student_names.append("new_student")`<br>**Error:** AttributeError - tuples don't have append method |
| Syntax: `[]` | Syntax: `()` |
| Used when data changes | Used when data is fixed |
