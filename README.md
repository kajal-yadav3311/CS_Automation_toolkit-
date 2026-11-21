# 🛡️ Cybersecurity & Networking Toolkit (`cs-toolkit`)

A collection of lightweight, custom Python utilities designed for automated security auditing, vulnerability scanning, and network communication. 

---

## 🚀 Projects Included in This Toolkit

### 1. 🔍 Sensitive Data & Information Leakage Scanner
* **Description:** An automated Python security tool that recursively inspects local directories for hardcoded credentials, API keys, and Personally Identifiable Information (PII).
* **Key Features:**
  * Uses `os.walk` for deep directory traversal.
  * Implements multi-pattern Regular Expressions (`re`) to detect AWS IAM keys (`AKIA`/`ASIA`), email addresses, and generic secret assignments.
  * Generates timestamped audit reports (`scan_report.txt`) for vulnerability triage.

### 2. 📧 Phishing Email Scanner
* **Description:** A text-based risk-scoring utility that evaluates incoming email content to classify potential phishing threats.
* **Key Features:**
  * Keyword-based risk scoring for high-urgency and financial trigger words.
  * Automated URL/domain detection (`http`/`.com`) and punctuation analysis (excessive `!`).
  * Continuous interactive loop (`while True`) providing real-time security status and red-flag summaries.

### 3. 🔌 TCP Client-Server Socket Chat
* **Description:** A robust TCP/IP socket programming implementation enabling bidirectional message exchange between a client and a server.
* **Key Features:**
  * Built using Python's native `socket` module.
  * Structured multi-message exchange loop with proper exception handling (`ConnectionRefusedError`, `OSError`).
  * Clean resource management ensuring safe socket closure via `finally` blocks.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Core Modules:** `os`, `re`, `datetime`, `socket`

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/kajal-yadav3311/cs-toolkit.git](https://github.com/kajal-yadav3311/cs-toolkit.git)
   cd cs-toolkit

   Run the Sensitive Data Scanner:

Bash
python data_scanner.py
Run the Phishing Scanner:

Bash
python phishing_scanner.py



