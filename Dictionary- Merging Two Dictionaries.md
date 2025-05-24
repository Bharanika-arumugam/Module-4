## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To Write a Python program to convert them into a dictionary in a way that item from list1 is the key and item from list2 is the value. Get two lists as input.

## 🧠 Algorithm
1.Start

2.Prompt the user to input a list of keys (e.g., ['a', 'b', 'c'])

3.Store the input in a variable called keys

4.Prompt the user to input a list of values (e.g., [1, 2, 3])

5.Store the input in a variable called values

6.Convert the keys input string to an actual list using eval() or ast.literal_eval()

7.Convert the values input string to an actual list

8.Combine the keys and values into pairs using the zip() function

9.Create a dictionary from the zipped pairs using the dict() function

10.Print the resulting dictionary

11.End
## 🧾 Program
``` python
keys = input()
values = input()
keys_list = eval(keys)
values_list = eval(values)
result = dict(zip(keys_list, values_list))
print(result)
```

## Output
![image](https://github.com/user-attachments/assets/200b8898-ca1e-4101-a571-650bd5daf6fd)

## Result
Thus the python program to convert the input into dictionary is executed successfully.

