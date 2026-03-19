## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
Add code Here
<img width="1920" height="1080" alt="Screenshot 2026-03-19 083004" src="https://github.com/user-attachments/assets/8efef294-2ef4-4e70-8054-1961e6f08c6d" />

## Output
<img width="1920" height="1080" alt="Screenshot 2026-03-19 083004" src="https://github.com/user-attachments/assets/81c96a97-ed47-4b54-af80-ac68656b4a0e" />

## Result
Thus the program was successfully executed.and obtained the result
