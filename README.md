# 🔐 Flask Brute Force Attack Demo

A deliberately vulnerable Flask-based authentication application designed to demonstrate **Brute Force Attacks** using **Burp Suite Intruder**. This project is intended for cybersecurity education, ethical hacking labs, and understanding authentication vulnerabilities in web applications.

---

## 📖 Overview

This project simulates a simple login system with intentionally weak authentication controls. It allows learners to observe how attackers can automate login attempts using Burp Suite and understand the importance of implementing secure authentication mechanisms.

> **⚠️ Educational Purpose Only**
>
> This application is intentionally insecure and should only be used in controlled lab environments for learning and security testing.

---

## 🚀 Features

* Flask-based login system
* Admin authentication
* Protected dashboard
* Login and logout functionality
* Vulnerable to brute-force attacks
* Compatible with Burp Suite Intruder demonstrations
* Simple UI built with HTML, CSS, and Bootstrap

---

## 🛠️ Tech Stack

* Python
* Flask
* HTML5
* CSS3
* Bootstrap
* Burp Suite Community Edition

---

## 📂 Project Structure

```
brute-force-demo/
│
├── app.py
├── requirements.txt
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   └── products.html
│
├── static/
│   ├── css/
│   └── images/
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/flask-brute-force-demo.git
cd flask-brute-force-demo
```

Create a virtual environment (optional):

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5000
```

---

## 🔑 Demo Credentials

```
Username : admin
Password : adminpassword
```

---

## 🧪 Demonstrating a Brute Force Attack

1. Start the Flask application.
2. Configure your browser to use Burp Suite as a proxy.
3. Capture the login POST request.
4. Send the request to **Intruder**.
5. Mark the password field as the payload position.
6. Load a custom password wordlist.
7. Launch the attack.
8. Analyze the responses to identify the valid credentials.

---

## 🔍 Security Weaknesses Demonstrated

* Unlimited login attempts
* No account lockout
* No rate limiting
* No CAPTCHA protection
* Hardcoded credentials
* Username enumeration
* No password hashing
* No session-based authentication
* Insecure authentication workflow

---

## 🛡️ Recommended Security Improvements

* Password hashing using bcrypt
* Secure session management
* Account lockout after multiple failed attempts
* Rate limiting
* CAPTCHA or reCAPTCHA
* Generic authentication error messages
* Multi-Factor Authentication (MFA)
* HTTPS enforcement
* Database-backed user authentication

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How web authentication works
* HTTP GET and POST requests
* Authentication vulnerabilities
* Burp Suite Proxy and Intruder
* Brute-force attack methodology
* Secure authentication design
* Defensive security best practices

---


## 📚 Skills Demonstrated

* Flask Development
* Web Security
* Authentication
* Burp Suite
* Penetration Testing Fundamentals
* HTTP Request Analysis
* Vulnerability Assessment
* Cybersecurity Lab Development

---

## ⚠️ Disclaimer

This project is developed **strictly for educational and ethical cybersecurity training purposes**. Do **not** use these techniques against systems you do not own or do not have explicit authorization to test. Unauthorized security testing may violate laws and organizational policies.

---

## 👨‍💻 Author

**Soumya Hazra**

* Cybersecurity Enthusiast
* SOC Analyst Aspirant
* GitHub: https://github.com/Soumya-CSE
