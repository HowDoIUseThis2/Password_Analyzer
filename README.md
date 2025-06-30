# Password_Analyzer
Basic Password Analyzer
# 🔐 Password Strength Analyzer

A lightweight, zero-dependency command-line tool that evaluates the strength of a password based on common best practices. Ideal for developers, cybersecurity students, and system administrators seeking a quick and portable way to audit credentials.

---

## 🚀 Features

- ✅ Checks for:
  - Minimum and strong-length thresholds (8+ / 12+ characters)
  - Uppercase and lowercase letters
  - Numbers and special symbols
  - Commonly known insecure words (e.g., "admin", "password")
- 🎯 Score-based feedback with checklist-style output
- 🌀 Interactive terminal experience with animated analysis
- 📦 No external libraries or dependencies required

---

## 🧠 Evaluation Criteria

| Criteria                     | Description                                 |
|-----------------------------|---------------------------------------------|
| Length ≥ 8                  | Minimum standard for moderate security      |
| Length ≥ 12                 | Recommended for strong passwords            |
| Uppercase letter            | Improves entropy and complexity             |
| Lowercase letter            | Adds diversity and pattern resistance       |
| Numeric digit               | Increases difficulty to brute-force         |
| Special character (symbol)  | Defeats dictionary and rainbow table attacks|
| No common dictionary word   | Protects against known weak terms           |

---

## 💻 Usage

### 🔧 Requirements

- Python 3.6 or higher

### ▶️ How to Run

1. Clone or download the repository:

   ```bash
   git clone https://github.com/HowDoIUseThis2/Password_Analyzer.git
   cd Password_Analyzer
