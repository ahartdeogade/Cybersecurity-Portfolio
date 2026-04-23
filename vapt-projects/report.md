# 🛡️ Web Application VAPT Report

## 🎯 Target
**demo.tesfire.net (Demo Environment)**

## ⚠️ Disclaimer
Testing performed on a publicly accessible demo environment for educational purposes only.

---

# 🔍 Vulnerability 1: Cross-Site Scripting (XSS)

<details>
<summary>📌 Click to Expand Details</summary>

### 📖 Description
The application fails to sanitize user input, allowing execution of JavaScript.

### 💣 Payload Used
<script>alert('this is dangerous')</script>

### 🎯 Impact
- Session hijacking  
- Cookie theft  
- Malicious script execution  

### 🛠️ Remediation
- Input validation  
- Output encoding  
- Use CSP headers  

</details>

---

# 🔍 Vulnerability 2: HTML Injection

<details>
<summary>📌 Click to Expand Details</summary>

### 📖 Description
User input is rendered without sanitization, allowing HTML injection.

### 💣 Payload Used
<img src="https://miro.medium.com/v2/resize:fit:1400/0*y2OAF_DSarBAjihO.jpg" width="500"> ```

### 🎯 Impact
- UI manipulation
- Phishing attacks
- Content spoofing

### 🛠️ Remediation
- Sanitize HTML input
- Use output encoding

</details>

---

# 🔍 Vulnerability 3: SQL Injection

<details> 
<summary>📌 Click to Expand Details</summary>

### 📖 Description
Improper input validation allows SQL query manipulation.

### 💣 Payload Used
'or 1=1 --

### 🎯 Impact
- Authentication bypass
- Unauthorized access
- Database compromise

### 🛠️ Remediation
- Use prepared statements
- Parameterized queries
- Input validation

</details>

---

# 📊 Summary

<details>
<summary>📌 Click to Expand Details</summary>
  
Vulnerability	Risk Level
🔴 XSS	High
🔴 SQL Injection	Critical
🟡 HTML Injection	Medium

</details>

---

# 🧰 Tools Used
<details>
<summary>📌 Click to Expand Details</summary>
  
- Burp Suite
- Browser DevTools
- Manual Testing

</details>

---

# 📂 Additional Resources
<details>
<summary>📌 Click to Expand Details</summary>
  
- 👉 View Payloads
- 👉 Screenshots

</details>
