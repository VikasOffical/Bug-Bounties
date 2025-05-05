# **🐞 Bug Bounty Report | Internship Task-3**

> **🔍 Hunt | 🛡️ Detect | ✍️ Report – A Practical Approach to Web Security Testing Using DVWA, Burp Suite & OWASP ZAP**

---

## **📌 Project Overview**

This project is a **hands-on bug bounty simulation** conducted in a safe, ethical hacking environment using **DVWA** (Damn Vulnerable Web App). It demonstrates the identification of critical web application vulnerabilities like **SQL Injection** and **Cross-Site Scripting (XSS)** using industry-standard tools.

---

## **🧾 Internship Details**

- 👨‍💻 **Name:** Gyanmotay Vikas  
- 🆔 **Intern ID:** CT12RGV  
- 🏢 **Company:** Codetech IT Solutions  
- 🌐 **Domain:** Cybersecurity & Ethical Hacking  
- 📅 **Duration:** 8 Weeks  
- 🧑‍🏫 **Mentor:** Nella Santosh  

---

## **🛠️ Tools & Environment**

| **Tool / Platform**  |**Role in Testing**                  |
|------------------|-------------------------------------------|
| 💻 DVWA          | Vulnerable web app for practice           |
| 🧪 Burp Suite    | Manual testing and traffic interception   |
| ⚙️ OWASP ZAP     | Automated vulnerability scanner           |
| 🌐 XAMPP         | Localhost server to host DVWA             |
| 🔎 Browser       | UI interaction and payload injection      |

---

## 🚀 Bugs Discovered

### **✅ SQL Injection**

- **Vector:** `' OR 1=1 --`  
- **Effect:** Bypasses login, extracts data  
- **Tool:** Burp Suite (Repeater)  
- ![SQLi Screenshot](screenshots/sql-injection.png)

---

### **✅ Cross-Site Scripting (XSS)**

- **Vector:** `<script>alert('XSS')</script>`  
- **Effect:** JavaScript execution in browser  
- **Tool:** OWASP ZAP & Burp Suite  
- ![XSS Screenshot](screenshots/xss-attack.png)

---

## **🔍 Step-by-Step Methodology**

1. ✅ Set up DVWA on localhost using XAMPP  
2. ✅ Configure DVWA security level to "Low"  
3. ✅ Launch Burp Suite → intercept & analyze requests  
4. ✅ Test forms manually for SQLi and XSS  
5. ✅ Perform automated scans with OWASP ZAP  
6. ✅ Document findings and screenshots  

---

## **📚 Key Takeaways**

- 🔐 Gained practical exposure to **bug bounty techniques**  
- 🛠️ Used real-world tools in a **legal testing environment**  
- 📄 Learned professional **report writing** and vulnerability documentation  
- 🌐 Understood the importance of **secure input handling**

---

## **📁 Project Structure**

**Bug-Bounty-Task/
├── README.md
├── screenshots/
│ ├── sql-injection.png
│ └── xss-attack.png
├── report/
│ └── bug_bounty_report.pdf
└── findings.txt**

---

##  **📜 Disclaimer**

### > This project is for **educational and ethical use only**. All testing was conducted in a legal environment. Never test websites or apps without proper authorization.
---

## **👨‍💻 Author**

**Gyanmotay Vikas**  
🔗 GitHub: [VikasOfficial](https://github.com/VikasOffical)  
🔗 LinkedIn: [linkedin.com/in/gyanmotay-vikas-62471126b](https://linkedin.com/in/gyanmotay-vikas-62471126b)

---

## **⭐ Support & Feedback**

If this project helped you learn, please ⭐ star this repository!  
Feedback, suggestions, or improvements? Open an issue or reach out on [LinkedIn](https://linkedin.com/in/gyanmotay-vikas-62471126b).

---

**> _“Bug bounty hunting is not just finding flaws, it's understanding the system.”_**
