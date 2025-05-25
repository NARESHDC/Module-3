# 1:List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
list=[1,2,-8]
total=sum(list)
print(total)
```

## Output
![mod3-1](https://github.com/user-attachments/assets/8f97ff56-6439-4d28-ab2d-099be3a16965)

## Result
Thus,the program has been executed successfully.

# 2:Regex in Python: Filter Words Without the Letter 'e'

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
l1=[]
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
for i in items:
   if not re.search(r"e",i):
      l1.append(i)
print(l1)
```
## Output
![mod3-2](https://github.com/user-attachments/assets/da50428b-7951-4627-8379-269cb0c0e564)

## Result
Thus,the program has been executed successfully.

# 3:🧹 Strings-Remove Nth Index Character from a String

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
  l=len(str)
a=""
n=int(input())
for i in range(0,l):
  if i==n:
    a=a+""
  else:
    a=a+str[i]
print(a)

```

## Output
![mod3-3](https://github.com/user-attachments/assets/57753e76-e25b-4049-960d-363979105164)

## Result
Thus,the program has been executed successfully.

# 4:Strings-Palindrome Check in Python (Without Built-in Functions)

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
string="google"
if string==string[::-1]:
   print ("The entered string is palindrome") 
else:
   print ("The entered string is not palindrome")
```

## Output
![mod3-4](https://github.com/user-attachments/assets/38a4c0da-d7ad-44eb-8fac-9453b2dded19)

## Result
Thus,the program has been executed successfully.

# 5:Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
tuplex = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in tuplex)
print("8" in tuplex)

```
## Output
![mod3-5](https://github.com/user-attachments/assets/036f3474-5176-4430-a124-9036a778d11d)

## Result
Thus,the program has been execueted successfully.
