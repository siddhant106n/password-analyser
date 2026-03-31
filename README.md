🔐 Password Strength Analyzer (AI-Inspired)
A smart and lightweight Password Strength Analyzer built using Python that evaluates how secure a password is and provides actionable suggestions to improve it.
Unlike traditional rule-based systems, this tool is inspired by modern AI-based security approaches, focusing on real-world password weaknesses such as patterns, predictability, and repetition.
📌 Project Overview
Traditional password systems rely on simple rules like minimum length, uppercase letters, or numbers. These rules are easy to bypass using predictable passwords like School@123.
This project introduces a smarter approach:
Evaluates password strength using multiple weighted factors
Detects weak patterns and predictable sequences
Penalizes repeated characters
Generates a security score out of 100
Provides personalized suggestions
This simulates how AI-driven systems analyze password strength based on complexity and randomness, not just basic rules.
⚙️ Features
✅ Score-based password evaluation (0–100)
🔍 Detects weak sequences (e.g., abc, 123, 987)
🔁 Detects repeated characters (e.g., aaa, 111)
📊 Provides detailed feedback and suggestions
💡 Simple and clean Command-Line Interface (CLI)
⚡ No external libraries required
🧠 Scoring Logic
The password is evaluated using the following criteria:
Length Bonus (25 points)
Full points for ≥10 characters, partial for >6 and >8
Uppercase Letters (15 points)
At least one uppercase letter (A–Z)
Lowercase Letters (15 points)
At least one lowercase letter (a–z)
Digits (20 points)
At least one number (0–9)
Special Characters (25 points)
At least one symbol (!@#$%^&*, etc.)
🚫 Penalties
Common sequences like abc, 123, zyx
Repeated characters like aaa, 111
📊 Rating System
90 – 100 → Strong Password 🟢
75 – 89 → Moderate 🟡
50 – 74 → Weak 🟠
25 – 49 → Very Weak 🔴
< 25 → Not Valid ❌
🛠️ Technologies Used
Python 3.x
Built-in module: string
Command Line Interface (CLI)
🚀 Steps to Run the Code
1. Save the Code
Save the script as:
password_analyzer.py
2. Run the Program
Open terminal or command prompt and run:
python password_analyzer.py
3. Enter Password
### Password Strength Analyzer ###
Enter your password:
🧪 Example Output
### PASSWORD ANALYSIS ###

Analyzed Password: hello
Final Score: 30 / 100
Rating: Very Weak

Suggestions:
--> Add uppercase letters  
--> Add digits  
--> Add special characters  
--> Increase password length (recommended: 10+)  
📂 Project Structure
password-analyzer/
│── password_analyzer.py
│── README.md
🔧 Function Breakdown
analyze(password)
Evaluates password strength using scoring logic and penalties
rate(score)
Converts score into a readable rating
result(password, score, feedback)
Displays final output and suggestions
main()
Handles input and runs the program
🎯 Future Improvements
🔐 AI/ML-based password strength prediction
🌐 Web-based interface
⏱️ Password cracking time estimation
🗃️ Integration with real-world leaked password datasets
👨‍💻 Author
Siddhant Bandil
