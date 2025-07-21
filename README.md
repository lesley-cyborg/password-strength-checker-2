# 🔐 Password Strength Checker 2

A Python-based password strength checker with:

- ✅ GUI using Tkinter  
- 🔐 Checks against [HaveIBeenPwned](https://haveibeenpwned.com/API/v3) breach database  
- 📊 Entropy-based strength meter  
- 🌙 Dark mode GUI  
- 💾 Save report feature  

---

## 📸 Screenshot

![screenshot](screenshots/demo.png) <!-- Add an actual screenshot in your repo folder -->

---

## ⚙️ Features

| Feature              | Description                                       |
|----------------------|---------------------------------------------------|
| GUI Interface        | Built with Tkinter and styled with dark mode     |
| Entropy Meter        | Displays strength in real-time (0% to 100%)       |
| Breach Detection     | Uses k-Anonymity with HaveIBeenPwned API         |
| Weak Password Check  | Flags short, simple, or dictionary passwords      |
| Save Report          | Allows exporting feedback as `.txt` file         |

---

## 🔧 Installation

### Requirements

- Python 3.7+
- `requests` library

```bash
pip install requests
