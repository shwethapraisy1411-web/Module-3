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

<img width="700" height="319" alt="image" src="https://github.com/user-attachments/assets/8dba2af8-ab57-4117-b7aa-f44beb6a35ca" />

## Output
<img width="453" height="226" alt="image" src="https://github.com/user-attachments/assets/c6246ae1-4bd1-434d-b448-cf3a70d5e874" />

## Result
The output is verified successfully.
