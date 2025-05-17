# 🔁 Control Flow: Age Access Checker Project

Welcome to **Chapter 3: Control Flow (If/Else)**! In this beginner-friendly Python project, you'll learn how to make decisions in your code using `if`, `elif`, and `else` statements — plus how Boolean logic and indentation matter in real-world programming.

---

## 📌 What You'll Learn

* ✅ How `if`, `elif`, and `else` statements work
* ✅ The importance of indentation in Python
* ✅ How to combine conditions using `and` and `or`
* ✅ Making code respond to different types of user input
* ✅ Structuring basic logic flow in a real-world example

---

## 💡 About the Project

This simple project — **Age Access Checker** — asks the user for their age and tells them what activities they’re allowed to do:

* Are they a kid, teen, or adult?
* Can they vote? Drive? Rent a car?
* What if they enter something weird or invalid?

You’ll also see how forgetting indentation can break your code, and how logical operators like `and` and `or` can be used to handle more complex decisions.

---

## 🧱 Project Code

```python
# 🔁 Age Access Checker

# Step 1: Get user input and make sure it's a number
age_input = input("Enter your age: ")

if age_input.isdigit():
    age = int(age_input)

    # Step 2: Basic decision-making using if/elif/else
    if age < 13:
        print("You're a kid! 🧒")
    elif age < 18:
        print("You're a teenager! 👦👧")
    else:
        print("You're an adult! 🧑")

    # Step 3: Advanced access logic using Boolean expressions
    if age >= 18:
        print("✅ You can vote.")
    if age >= 16 and age < 18:
        print("🚗 You might be able to get a driving permit.")
    if age >= 21:
        print("🍻 You can legally drink (in many countries).")
    if age >= 25:
        print("🚘 You can rent a car without extra fees.")

else:
    print("❌ Please enter a valid number for age.")

# Common mistake: no indentation after 'if' would cause an error
# if age > 18:
# print("You're an adult!")  ← This would cause an IndentationError
```

---

## 🧠 Breakdown of Concepts

| Concept              | Shown In                            |
| -------------------- | ----------------------------------- |
| `if`, `elif`, `else` | Age group checks                    |
| `input()`            | User interaction                    |
| `isdigit()`          | Validating input                    |
| `int()`              | Type conversion                     |
| `and`, `or`          | Complex logic for driving & renting |
| Indentation rules    | Shown in code comment example       |

---

## 🧮 How to Run This Project

1. Make sure you have **Python 3** installed.
2. Save the code above in a file named `age_access_checker.py`
3. Open your terminal and run:

   ```bash
   python age_access_checker.py
   ```
4. Try different age values and see how the program responds!

---

## 🎯 Try These Bonus Challenges

* Add custom messages for ages over 100 (👴)
* Handle invalid input (like letters or symbols)
* Add country-specific age logic (like voting at 16 in Austria)
* Offer suggestions like "Come back in X years to rent a car!"

---

🐍 This is part of the **Pythonly beginner series**.
Learn Python one line at a time. Follow [@Pythonly](https://github.com/Pythonlyy) for more.
