# 🔐 Password Strength Analyzer

An intelligent Password Strength Analyzer built using Python that evaluates the security level of user passwords and provides actionable feedback to improve them.

This project goes beyond basic rule-checking and simulates a real-world security evaluation system by analyzing password complexity, randomness, and common attack patterns.

---

## 📌 Project Overview

Traditional password validation systems rely on simple rules such as minimum length or inclusion of special characters. However, these rules are often predictable and can be easily bypassed using weak but rule-compliant passwords (e.g., "School123!").

This project introduces a smarter approach inspired by Artificial Intelligence concepts. Instead of only checking rules, it evaluates:

- Pattern predictability
- Character diversity
- Randomness of input
- Common vulnerabilities like sequences and repetition

It then generates a **risk-based score** and estimates how secure the password is in real-world scenarios.

---

## 🚀 Key Features

- 🔍 **Comprehensive Password Analysis**  
  Evaluates multiple aspects of password strength including length, diversity, and structure.

- 🧠 **AI-Inspired Risk Evaluation**  
  Simulates intelligent security analysis instead of basic rule checking.

- ⚡ **Real-Time Feedback System**  
  Provides instant suggestions to improve weak passwords.

- 🛡️ **Pattern Detection Engine**  
  Detects common weak patterns like:
  - Sequential characters (`abc`, `123`)
  - Repetitions (`aaa`, `111`)

- 📊 **Scoring System (0–100 Scale)**  
  Assigns a detailed strength score for better understanding.

---

## ⚙️ Scoring Logic

The password is evaluated on a **100-point scale** based on the following criteria:

| Criteria              | Points |
|----------------------|--------|
| Length Bonus         | 25     |
| Uppercase Letters    | 15     |
| Lowercase Letters    | 15     |
| Digits               | 20     |
| Special Characters   | 25     |

### ⚠️ Penalties Applied:
- ❌ Sequential patterns (e.g., `abc`, `123`)
- ❌ Repeated characters (e.g., `aaa`, `111`)

---

## 📈 Rating System

| Score Range | Security Level |
|------------|---------------|
| 90 – 100   | Strong Password ✅ |
| 75 – 89    | Moderate Strength ⚠️ |
| 50 – 74    | Weak ❌ |
| 25 – 49    | Very Weak ❗ |
| < 25       | Critical Risk 🚨 |

---

## 🛠️ Technologies Used

- **Programming Language:** Python 3.x  
- **Library Used:**  
  - `string` (for handling character sets)  
- **Interface:** Command Line Interface (CLI)

---

## ▶️ How to Run

### 1️⃣ Save the File
Save the code as:

```bash
password_analyzer.py
