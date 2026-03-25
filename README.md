📘 Python Program: Check Even or Odd Number
📌 Overview

This Python program checks whether a given number is Even or Odd using a mathematical logic based on division.

Instead of using the common modulus operator (%), this program uses an alternative method:

(
𝑛
𝑢
𝑚
/
/
2
)
∗
2
=
=
𝑛
𝑢
𝑚
(num//2)∗2==num
⚙️ Source Code
num = int(input("Enter the number: "))

if (num // 2) * 2 == num:
    print("Even Number")
else:
    print("Odd Number")
🧠 How It Works
1️⃣ Take Input from User
num = int(input("Enter the number: "))
input() takes user input.
int() converts the input into an integer.
2️⃣ Check Condition
if (num // 2) * 2 == num:
// is floor division (removes decimal part).
The number is divided by 2 and multiplied back.

👉 If the result is equal to the original number → Even
👉 If not → Odd

3️⃣ Print Result
print("Even Number")

or

print("Odd Number")
🔄 Example Execution
Input
Enter the number: 6
Calculation
(6 // 2) * 2 = 3 * 2 = 6
Output
Even Number
Another Example
Input
Enter the number: 7
Calculation
(7 // 2) * 2 = 3 * 2 = 6 ≠ 7
Output
Odd Number
🔑 Key Concepts Demonstrated
User input handling
Integer division (//)
Conditional statements (if-else)
Logical comparison
⏱️ Time Complexity

O(1) — Constant time operation.

🚀 Alternative (More Common Method)
if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")

👉 % (modulus) directly checks remainder.

📚 Learning Outcome

After understanding this program, you will learn:

Different ways to check even/odd numbers
How division and multiplication can be used logically
How conditional statements work in Python
