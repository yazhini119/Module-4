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
keys = input()
values = input()
keys_list = eval(keys)
values_list = eval(values)
result = dict(zip(keys_list, values_list))
print(result)
```

## Output
<img width="1200" height="341" alt="447234400-200b8898-ca1e-4101-a571-650bd5daf6fd" src="https://github.com/user-attachments/assets/44e13d3d-f033-4426-96a2-a93b63d3baf6" />

## Result
Thus the python program to convert the input into dictionary is executed successfully.
