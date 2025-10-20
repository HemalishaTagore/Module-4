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
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30}
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50}
def merge (dict1,dict2): 
   res={**dict1 , **dict2}
   return res 
dict3=merge(dict1,dict2)
print(dict3)
```
## Output
<img width="815" height="306" alt="Screenshot 2025-10-20 152800" src="https://github.com/user-attachments/assets/6f8e5828-2c7a-4549-88bf-4f334845e413" />

## Result
Thus, to write a Python program that merges **two dictionaries** and combines their key-value pairs is executed successfully.
