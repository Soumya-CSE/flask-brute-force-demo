# 🔐 Flask Brute Force Attack Demo using Burp Suite

> A deliberately vulnerable Flask authentication application designed to demonstrate **Brute Force attacks** using **Burp Suite Intruder** for cybersecurity education, ethical hacking labs, and secure authentication awareness.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-Community-orange)
![License](https://img.shields.io/badge/License-Educational-red)

---

# 📖 Overview

Authentication is the first layer of security in any web application. Weak authentication mechanisms can allow attackers to gain unauthorized access through password guessing or brute-force attacks.

This project demonstrates how a vulnerable Flask login application can be exploited using **Burp Suite Intruder**. It is designed to help students understand authentication vulnerabilities, HTTP request analysis, brute-force attacks, and secure authentication practices.

> **⚠ Educational Purpose Only**
>
> This application is intentionally vulnerable and should only be used in a controlled lab environment for learning and security testing.

---

# 🎯 Project Objectives

- Build a Flask-based authentication system
- Understand Authentication & Authorization
- Learn HTTP GET and POST requests
- Demonstrate Brute Force attacks using Burp Suite
- Analyze HTTP requests and responses
- Identify authentication vulnerabilities
- Learn secure coding and mitigation techniques

---

# 🚀 Features

- Flask-based Login System
- Admin Authentication
- Protected Dashboard
- Login & Logout Functionality
- Burp Suite Intruder Compatible
- Demonstrates Brute Force Vulnerability
- Simple Responsive UI
- Educational Security Lab

---

# 🛠 Tech Stack

## Backend

- Python
- Flask

## Frontend

- HTML5
- CSS3
- Bootstrap

## Security Tools

- Burp Suite Community Edition

---

# 📂 Project Structure

```text
BRUTE-FORCE/
│
├── app.py
├── dashboard.html
├── user.txt
├── README.md
│
├── templates/
│   ├── admin.html
│   ├── login.html
│   ├── products.html
│   └── register.html
│
└── static/
    ├── aws.png
    ├── cyber.jfif
    ├── react.png
    └── Screenshot 2024-04-14 192823.png
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/flask-brute-force-demo.git
```

## Navigate to Project

```bash
cd flask-brute-force-demo
```

## Install Dependencies

```bash
pip install flask
```

## Run the Application

```bash
python app.py
```

## Open Browser

```
http://127.0.0.1:5000
```

---

# 🔑 Demo Credentials

```
Username : admin
Password : adminpassword
```

---

# 🛰 Project Architecture

```
Browser
   │
   ▼
Login Page
   │
POST Request
   │
   ▼
Flask Server
   │
Credential Validation
   │
 ┌───────────────┐
 │               │
 ▼               ▼
Success        Failure
 │               │
 ▼               ▼
Dashboard    Login Page
```

Burp Suite acts as a proxy between the browser and Flask server, allowing HTTP requests to be intercepted, modified, and replayed.

---

# 🔄 Authentication Workflow

1. User enters username and password.
2. Browser sends a POST request to the Flask server.
3. Flask validates the credentials.
4. If credentials are correct, the dashboard is displayed.
5. Otherwise, an authentication error is returned.

---

# 🧪 Brute Force Attack Demonstration

1. Start the Flask application.
2. Open Burp Suite.
3. Configure the browser proxy.
4. Capture the login POST request.
5. Send the request to Intruder.
6. Select the password parameter as the payload position.
7. Load a custom password wordlist.
8. Launch the attack.
9. Compare HTTP responses.
10. Identify the correct credentials.

---

# 🔍 Vulnerabilities Demonstrated

- Unlimited Login Attempts
- No Account Lockout
- No Rate Limiting
- No CAPTCHA
- Hardcoded Credentials
- Username Enumeration
- Plain Text Password Storage
- No Password Hashing
- No Secure Session Management
- No HTTPS
- Information Leakage Through HTTP Responses

---

# 🛡 Security Improvements

- Account Lockout
- Password Hashing (bcrypt)
- CAPTCHA / reCAPTCHA
- Rate Limiting
- Multi-Factor Authentication (MFA)
- HTTPS
- Secure Session Management
- Database Authentication
- Generic Error Messages
- Strong Password Policy

---

# 🛰 Burp Suite Modules Used

- Proxy
- Intruder
- Repeater

---

# 📚 Learning Outcomes

After completing this project, you will understand:

- Authentication & Authorization
- Flask Authentication Workflow
- HTTP Requests and Responses
- Burp Suite Proxy
- Burp Suite Intruder
- Brute Force Attack Methodology
- Authentication Vulnerabilities
- Secure Authentication Design
- Defensive Security Practices

---

# 🧠 MITRE ATT&CK Mapping

| Attack | MITRE ATT&CK |
|---------|--------------|
| Brute Force | T1110 |
| Password Guessing | T1110.001 |
| Valid Accounts | T1078 |
| Adversary-in-the-Middle | T1557 |


---

# 🚀 Future Enhancements

- Database Integration
- bcrypt Password Hashing
- Flask Sessions
- User Registration
- CAPTCHA
- Multi-Factor Authentication
- JWT Authentication
- Login Activity Logs
- Rate Limiting
- Admin Dashboard
- SIEM Integration

---

# 💡 Skills Demonstrated

- Python
- Flask
- HTML5
- CSS3
- Bootstrap
- Web Authentication
- HTTP Protocol
- Burp Suite
- Web Penetration Testing
- Authentication Security
- Secure Coding
- Vulnerability Assessment
- Cybersecurity Fundamentals

---

# ⚠ Disclaimer

This project is developed **strictly for educational and ethical cybersecurity training purposes**.

Only perform penetration testing and brute-force demonstrations on systems you own or have explicit authorization to test.

Unauthorized testing of third-party systems is illegal and unethical.

---

# 👨‍💻 Author

**Soumya Kanti Hazra**

- 🎓 B.Tech CSE Student
- 🛡 SOC Analyst Aspirant
- 🔐 Cybersecurity Enthusiast

**GitHub:** https://github.com/Soumya-CSE
