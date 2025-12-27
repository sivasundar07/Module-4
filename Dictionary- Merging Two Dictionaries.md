## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
~~~

## Output
<img width="1208" height="354" alt="module4 exp2" src="https://github.com/user-attachments/assets/9cde662e-0ade-49b3-912a-479247f960ed" />

## Result
Thus the program executed successfully.
