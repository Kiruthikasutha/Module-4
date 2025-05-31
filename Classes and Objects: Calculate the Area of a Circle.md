# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
my_dict = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

# Sort by keys
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort by values
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)

```



## Output
![image](https://github.com/user-attachments/assets/811eeacf-3d5d-433f-bf1a-5e6007c701fb)

## Result
Thus the program has been successfully executed
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
    merged_dict = {**dict1, **dict2}
    return merged_dict

dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

result = merge(dict1, dict2)
print("Merged Dictionary:", result)
```
## Output
![image](https://github.com/user-attachments/assets/e68f698e-7c85-4209-86a3-4ed428b37b30)

## Result
Thus the program has been successfully executed

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0

with open("story.txt", "r") as file:
    for line in file:
        if not line.lstrip().startswith('T'):
            count += 1

print("Number of lines not starting with 'T':", count)

```
## Output
![image](https://github.com/user-attachments/assets/0099607c-c846-4975-88dd-4d61a612e0b1)

## Result
Thus the program has been successfully executed

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print("Accessing index 5:", list1[5])
except IndexError:
    print("You're out of list range")

```
## Output
![image](https://github.com/user-attachments/assets/cb9e0fa8-da4d-4426-a594-f22cef6312d3)


## Result
Thus the program has been successfully executed

# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class Saveetha:
    def __init__(self, r):
        self.area = math.pi * (r ** 2) 
    def slot(self):
        print("Area of circle:", round(self.area, 2))
r = float(input())
res = Saveetha(r)  
res.slot()
```


## Output
![439308211-353bddc7-e4f1-469f-9c7d-f8967d7e1aa3](https://github.com/user-attachments/assets/bcbed6ad-9fd0-45ca-926d-63ebbb5210fd)

## Result
Thus,the program has been executed successfully.

