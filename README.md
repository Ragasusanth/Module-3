
# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
def sum_list(items):
    sum_numbers = 0
    for x in items:
        sum_numbers += x
    return sum_numbers
print(sum_list([1,2,-8]))
```
## Output

![image](https://github.com/user-attachments/assets/d023116d-ba0f-4c39-a9e2-444b613f8404)

## Result

This program correctly calculates and prints the sum of all elements in the list using Python's built-in functionality

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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
filtered_items = [item for item in items if 'e' not in item]
print(filtered_items)
```
## Output

![image](https://github.com/user-attachments/assets/3c89abf1-a991-4657-bfb7-0b4fc93e7227)

## Result

This program successfully filters out and returns all elements that do not contain the letter 'e' using regular expressions.


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

![image](https://github.com/user-attachments/assets/4ac10bdc-b1a2-4d30-bf9b-e7cf4807b7a9)

## Result

This program successfully removes the character at the given index and returns the updated string


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
N=input()
if N==N[::-1]:
  print("palindrone")
else:
  print("not palindrone")
```
## Output

![image](https://github.com/user-attachments/assets/8f491986-c6bf-4064-82fe-a58819aa90e0)

## Result

The program correctly checks and reports whether "google" is a palindrome by reversing the string manually


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
my_tuple = eval(input())
is_n_not_exists = 'n' not in my_tuple
is_8_exists = '8' in my_tuple
print(is_n_not_exists)
print(is_8_exists)
```

## Output

![image](https://github.com/user-attachments/assets/352f7151-0274-4817-b2f3-76605a4f9814)

## Result

This program correctly uses the in operator to check for the presence of both a string and a number in a tuple.
