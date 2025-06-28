# prodigy-cs-03
# 🔐 Password Strength Checker

A simple Python script to evaluate the strength of a password based on commonly recommended security criteria. It also provides constructive feedback to help users create stronger passwords.

---

## 🚀 Features

- Checks if a password:
  - Has at least **8 characters**
  - Contains **lowercase** and **uppercase** letters
  - Includes at least one **digit**
  - Contains at least one **special character**
- Assigns a **strength score**: `Weak`, `Moderate`, or `Strong`
- Provides **feedback** to help improve weak passwords

---

## 🛠️ Requirements

- Python 3.x (no external libraries needed)

---

## ▶️ How to Run
python password_checker.py
Then, enter a password when prompted. The program will display the password strength and suggest improvements if needed.

✅ Example Output
Enter your password: Welcome123

Password Strength: Moderate
Suggestions:
- Include at least one special character.

---

### 🧠 Password Evaluation Criteria
Criteria	Points
Length ≥ 8	1
Contains lowercase letter	1
Contains uppercase letter	1
Contains digit	1
Contains special character	1

Total Score: 5

Strong: 5/5

Moderate: 3-4

Weak: 0-2

---

### 📂 File Structure
bash
Copy
Edit
password_checker.py   # Main script file
README.md             # Project documentation

---

### 👨‍💻 Author
Fahim Akthar
B.Tech Cyber Security | Crescent Institute of Science and Technology
