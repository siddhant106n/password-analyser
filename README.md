# 🔐 Password Strength Analyzer (AI-Inspired)

A smart and lightweight Password Strength Analyzer built using Python that evaluates how secure a password is and provides actionable suggestions to improve it.

Unlike traditional rule-based systems, this tool focuses on real-world password weaknesses such as patterns, predictability, and repetition.

---

## 📌 Project Overview

Traditional password systems rely on simple rules like minimum length, uppercase letters, or numbers. These rules are easy to bypass using predictable passwords like `School@123`.

This project introduces a smarter approach:

- Evaluates password strength using multiple factors  
- Detects weak patterns and sequences  
- Penalizes repeated characters  
- Generates a score out of 100  
- Provides suggestions for improvement  

---

## ⚙️ Features

- Score-based password evaluation (0–100)
- Detects weak sequences (abc, 123, etc.)
- Detects repeated characters (aaa, 111)
- Gives improvement suggestions
- Simple CLI-based tool
- No external libraries required

---

## 🧠 Scoring Logic

- Length (25 points)  
- Uppercase letters (15 points)  
- Lowercase letters (15 points)  
- Digits (20 points)  
- Special characters (25 points)  

### Penalties:
- Common sequences (abc, 123)
- Repeated characters (aaa, 111)

---

## 📊 Rating System

- 90–100 → Strong  
- 75–89 → Moderate  
- 50–74 → Weak  
- 25–49 → Very Weak  
- <25 → Invalid  

---

## 🛠️ Technologies Used

- Python 3  
- Built-in module: string  
- Command Line Interface  

---

## 🚀 How to Run

1. Save file as:password_analyzer.py

 
2. Run:python password_analyzer.py


3. Enter your password when prompted

---

## 🧪 Example Output

Analyzed Password: hello
Score: 30 / 100
Rating: Very Weak
Suggestions:
Add uppercase letters
Add digits
Add special characters
Increase length



---

## 📂 Project Structure


password-analyzer/
│── password_analyzer.py
│── README.md


---

## 👨‍💻 Author

Siddhant Bandil

---

