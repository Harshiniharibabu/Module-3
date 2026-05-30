# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
num=[1,2,3,4,5,6,7,8,9,10]
total=sum(num)
print("The sum of the numbers in the list is:", total)
```

## Output
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/814dcc30-39ab-4af6-b0d9-4da9b54d0ed3" />


## Result
Thus, the program is executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print(l1)
```
## Output
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/0dd2a78c-a6f4-44aa-8fcd-8f279eddb7c5" />

## Result
Thus, the program is executed successfully.

# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(str):
    n = int(input("Enter the index to remove: "))
    a = ""
    for j in range(len(str)):
        if j != n:
            a += str[j]
    return a
str1 = input("Enter a string: ")
print("Modified string:", remove(str1))
```
## Output
<img width="1909" height="1013" alt="image" src="https://github.com/user-attachments/assets/eb56ef7e-4996-4a19-b074-22f97d0e42e3" />

## Result
Thus, the program is executed successfully.

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
str='google'
rev=str[::-1]
if str==rev:
    print("The given string is a palindrome")
else:
    print("The given string is not a palindrome")
```

## Output
<img width="1918" height="1006" alt="image" src="https://github.com/user-attachments/assets/87455ee1-4e32-4b45-aa7d-6a5acca78457" />

## Result
Thus, the program is executed successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuple1=(2,4,6,8,'n','o','t','e')
print('n' in tuple1)
print(8 in tuple1)
```
## Output
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/bf4eba44-41a1-4608-9cea-6f27835fc0e2" />

## Result
Thus, the program is executed successfully.
