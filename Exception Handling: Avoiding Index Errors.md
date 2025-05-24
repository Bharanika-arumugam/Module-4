# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1.Start

2.Initialize an empty list a

3.Read an integer n from the user (number of elements to input)

4.Repeat the following n times:

a. Read an integer from the user

b. Append the integer to list a

5.Print the entire list a

6.Try to access and print the element at index 10 (11th element) from list a

7.If accessing index 10 causes an IndexError:

a. Print a message saying that the 11th element is not available (e.g., "10 is not accepted")

8.End


## 🧾 Program
``` python
try:
    a = []
    n = int(input())
    for i in range(n):
        b=int(input())
        a.append(b)
    print(a)
    print(a[10])
  

except IndexError:
   
    print("10 is not accepted")
```
## Output
![image](https://github.com/user-attachments/assets/bdc74ae9-6d48-431f-adda-801a0cfd739a)

## Result
Thus the a Python program that handles an **IndexError** is executed successfully.
