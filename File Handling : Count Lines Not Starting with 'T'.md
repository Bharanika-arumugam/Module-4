# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write Python function to find and replace a word in a file.

## 🧠 Algorithm
1.create_file(file_path, content)
Purpose: Creates a file and writes the specified content into it.

Opens the file in write mode ('w')—this overwrites the file if it already exists.

Writes the content into the file.

2. find_and_replace(file_path, old_word, new_word)
Purpose: Finds all instances of old_word in the file and replaces them with new_word.

How it works:

Opens the file in read mode, reads all contents.

Replaces all occurrences of old_word with new_word.

Opens the file in write mode and writes the updated content back.

3. read_file(file_path)
Purpose: Reads and returns the contents of a file.

How it works:

Opens the file in read mode and returns the entire content as a string

## 🧾 Program
``` python
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def find_and_replace(file_path, old_word, new_word):
    with open(file_path,'r')as f:
        cr=f.read()
        l=cr.replace(old_word,new_word)
    with open(file_path,'w') as f:
        f.write(l)


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
```
## Output
![image](https://github.com/user-attachments/assets/3cce9630-0e78-46ae-8047-d13e862e936c)

## Result
Thus the  Python function to find and replace a word in a file is executed successfully.
