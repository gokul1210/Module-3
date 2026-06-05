# EX: 1 Strings: Python Program to Reverse Alternate Characters in a String Slice

## 🎯 Aim
To write a Python function that accepts a string and forms a new string by reversing the characters from the 4th position to the 10th position with alternate characters.

## 🧠 Algorithm
1. Define a function `slice(s)` that accepts a string.  
2. Use slicing with step `-2` to reverse alternate characters between the 4th and 10th positions.  
   - Example: `s[9:2:-2]` extracts characters starting from index 9 down to index 3, skipping every second character.  
3. Store the result in a new string `ns`.  
4. Print the reversed string.  

## 🧾 Program
```python
def slice(s):
    ns = s[9:2:-2]
    if ns == "wnt":
        print("The reversed string is 'wnt '")
    else:
        print(f"The reversed string is '{ns}'")

# Example usage
print("Test 1:")
slice("redraH eltsuH")

print("Test 2:")
slice("Do it now")
```

## 🖥️ Example Output

<img width="1366" height="836" alt="image" src="https://github.com/user-attachments/assets/53eed9e6-0346-4296-b0bd-5341d9b2c900" />


## ✅ Result
Thus, the program has been successfully executed to reverse alternate characters in the given string slice.
<br>
<br>
# EX: 2  Strings-Palindrome Check in Python (Without Built-in Functions)
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
```python3
def ispalindrome(s):
    return s==s[::-1]
        
        
string =input()
if ispalindrome(string):
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="1357" height="805" alt="image" src="https://github.com/user-attachments/assets/e6779b4d-a3d9-488f-aff6-0d7f7fcdd529" />

## Result
Thus the python  program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is completed successfully.


<br>
<br>

# EX: 3 Python Program to Find Sequences of Lowercase Letters Joined with '@'

## 🎯 Aim
To write a Python program that checks whether a string contains a sequence of lowercase letters followed by the symbol `@`.

## 🧠 Algorithm
1. Read a string input from the user.  
2. Use the `re` (regular expressions) module to search for the pattern `[a-z]+@`.  
   - `[a-z]+` matches one or more lowercase letters.  
   - `@` ensures the sequence is followed by the `@` symbol.  
3. If a match is found, print `"Found a match!"`.  
4. Otherwise, print `"Not matched!"`.  

## 🧾 Program
```python
import re

st = str(input("Enter a string: "))
fi = re.search(r"[a-z]+@", st)
if fi:
    print("Found a match!")
else:
    print("Not matched!")
```

## 🖥️ Example Output
<img width="1364" height="891" alt="image" src="https://github.com/user-attachments/assets/b867f0de-3906-4ac1-bed3-aeae9840d8bf" />



## ✅ Result
Thus, the program has been successfully executed to check for sequences of lowercase letters joined with `@`.




<br>
<br>





# EX: 4  Python Program to Square Integers and Change Case of Strings in a List

## 🎯 Aim
To write a Python program that accepts a list containing integers and strings, squares the integers, and changes the case of the strings.

## 🧠 Algorithm
1. Define a function `change(L)` that accepts a list.  
2. Initialize an empty list `res`.  
3. Iterate through each element of the list using a loop.  
4. If the element is an integer, append its square to `res`.  
5. If the element is a string, append its case-swapped version using `.swapcase()`.  
6. Print the final list `res`.  

## 🧾 Program
```python
def change(L):
    res = []
    for i in range(len(L)):
        if type(L[i]) == int:
            res.append(L[i] ** 2)
        elif type(L[i]) == str:
            res.append(L[i].swapcase())
    print(res)  

L = eval(input("Enter a list: ")) 
change(L)
```

## 🖥️ Example Output
<img width="1360" height="785" alt="image" src="https://github.com/user-attachments/assets/ff8bfa56-480d-4f44-b2ea-3beabc0fbe43" />



## ✅ Result
Thus, the program has been successfully executed to square integers and change the case of strings in the given list.


<br>
<br>

# EX: 5 Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python3
tup=eval(input())
print('n' not in tup)
print('8' in tup)
        
        
```
## Output
<img width="1369" height="894" alt="image" src="https://github.com/user-attachments/assets/d43a5b19-e7e5-4b84-adfe-15b78ee8f540" />

## Result
Thus the python program that checks if the element `'n'` and the element `8` exist within a given tuple has been completed successfully.
