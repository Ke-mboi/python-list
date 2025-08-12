# Python List Assignment

This project demonstrates basic list operations in Python.

## Instructions Performed

1. **Create an empty list** called `my_list`.
2. **Append** the following elements to `my_list`: `10`, `20`, `30`, `40`.
3. **Insert** the value `15` at the second position in the list.
4. **Extend** `my_list` with another list: `[50, 60, 70]`.
5. **Remove** the last element from `my_list`.
6. **Sort** `my_list` in ascending order.
7. **Find and print** the index of the value `30` in `my_list`.

## Code

```python
my_list = []                                # Create empty list
my_list.extend([10, 20, 30, 40])            # Append elements
my_list.insert(1, 15)                       # Insert 15 at second position
my_list.extend([50, 60, 70])                 # Extend with another list
my_list.pop()                               # Remove last element
my_list.sort()                              # Sort in ascending order
print("The index of 30 is:", my_list.index(30))
print("Final my_list:", my_list)
