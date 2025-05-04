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
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output
![438328698-75f6d01f-afb0-4189-b9ba-6497464fa600](https://github.com/user-attachments/assets/1b523cd2-9ad2-41ef-be6d-9b1517f5b911)
![438328804-b2feb9ac-407d-4ee5-a669-0c2b55bb7173](https://github.com/user-attachments/assets/13336cf0-eaa2-4cc1-8f34-1bfbcc97e3a3)

## Result
Thus the program executed successfully.
