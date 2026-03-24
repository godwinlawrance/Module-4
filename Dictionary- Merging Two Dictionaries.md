## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
def merge(dict1, dict2):
    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

merged_dict = merge(dict1, dict2)
print("Merged Dictionary:", merged_dict)
```

## Output
<img width="659" height="115" alt="image" src="https://github.com/user-attachments/assets/f78a4170-8f5a-41f5-a3e3-d14c8efbfadd" />

## Result
The program successfully merges two dictionaries, combining their key-value pairs. If a key exists in both dictionaries, the value from the second dictionary overwrites the first.
