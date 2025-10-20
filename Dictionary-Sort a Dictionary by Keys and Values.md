# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
my_dict = {
    'France': 'Paris',
    'Japan': 'Tokyo',
    'India': 'New Delhi',
    'Brazil': 'Brasilia',
    'usa':'NewYork'
}

sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Original dictionary:", my_dict)
print("\nDictionary sorted by keys:", sorted_by_keys)
print("\nDictionary sorted by values:", sorted_by_values)
```

## Output
<img width="820" height="422" alt="Screenshot 2025-10-20 152954" src="https://github.com/user-attachments/assets/0d1f43cc-7613-4b60-a7d1-7ba98f431033" />

## Result
Thus, to write a Python program that sorts a dictionary is executed successfully.
