# **🛡️ CodeGuard: Python Bug Bounty Scanner**

**CodeGuard is an advanced static code analyzer built with Python that scans `.py` files for common security vulnerabilities and bad coding practices. This tool is ideal for bug bounty researchers, developers, and security interns.**


---
## **🚀 Features**

- 🔍 Detects dangerous functions like `eval()`, `exec()`, `os.system()`, `pickle.loads()`, etc.
- 📁 Recursively scans directories for Python files
- 💡 Highlights line numbers and specific security risks
- 🖥️ Optional HTML report generation for clean, shareable results

---

## **🧪 Sample Vulnerabilities Detected**

- Use of `eval()` or `exec()` (remote code execution)
- Unsafe use of `input()` without validation
- Insecure deserialization with `pickle.loads()`
- Shell command execution via `os.system()`

---

## **🛠️ How to Use**

### 1. Clone this repo or copy the script

```bash
git clone https://github.com/your-username/codeguard.git
cd codeguard
**2. Install Requirements**
bash
Copy
Edit
pip install -r requirements.txt
**3. Run the Scanner**
bash
Copy
Edit
# Scan a directory and generate HTML report
python codeguard_advanced.py test_code --html

# Scan a single file
python codeguard_advanced.py test_code/vulnerable.py --html
You’ll find the output in report.html after the scan.

📂Project Structure
**bash
Copy
Edit
Task-3/
├── codeguard.py                # Basic scanner (regex-based)
├── codeguard_advanced.py      # AST-based advanced scanner
├── test_code/                 # Test files with sample vulnerabilities
│   └── vulnerable.py
├── report.html                # Generated HTML report
├── requirements.txt
└── README.md**

📄License
This project is for educational and internship purposes only. Feel free to expand it, credit appreciated.

