## 📘 Project Overview

**Task: Password Strength Evaluation**.  
The objective of this task is to understand how password complexity impacts security and how weak passwords can be exploited through brute-force and dictionary attacks.

All password tests were performed practically on **Kali Linux (VirtualBox)** using **[PasswordMeter.com](https://passwordmeter.com)** for analysis.  
The results include password strength scores, complexity feedback, and best practices for creating secure passwords.

---

### 🧰 Tools & Environment
- Kali Linux (Virtual Machine)
- Firefox Browser
- PasswordMeter.com (Online Tool)
- Flameshot / gnome-screenshot (for screenshots)
- GitHub (for documentation and submission)

---

### 🎯 Objective
To evaluate multiple passwords of varying complexity and identify how factors like length, special characters, and randomness affect password strength.

---

### 🧩 Key Concepts
- Password Strength & Entropy  
- Brute-Force and Dictionary Attacks  
- Authentication Security  
- Password Complexity Best Practices  
- Multi-Factor Authentication (MFA)

---

## 📊 Password Evaluation Results

| Password Tested | Score (%) | Strength Level | Tool Feedback Summary |
|------------------|------------|----------------|------------------------|
| `password123` | 43% | Weak | Missing uppercase & special characters |
| `P@ssword123` | 58% | Medium | Better complexity, could use more symbols |
| `P@55w0rd!2025` | 78% | Strong | Good mix of characters and numbers |
| `Sru$hti_D@ve!2025` | 95% | Very Strong | Excellent use of symbols and case variation |
| `Sru$hti_D@ve!2025#Cyber@Security` | 100% | Excellent | Ideal password length and entropy |

---

## 🔍 Analysis

- **Password Length:** Longer passwords (15+ characters) significantly increase resistance to brute-force attacks.  
- **Character Variety:** Mixing uppercase, lowercase, numbers, and symbols creates higher entropy.  
- **Predictability:** Avoid using names, dates, or dictionary words.  
- **Entropy:** Each unique element (symbol, digit, case) increases entropy exponentially.  

---

## 🧠 Common Password Attacks

| Attack Type | Description | Prevention |
|--------------|-------------|-------------|
| **Brute Force Attack** | Systematically tries every possible combination. | Use long, complex passwords. |
| **Dictionary Attack** | Uses a list of common passwords or words. | Avoid dictionary-based passwords. |
| **Phishing** | Tricks users into revealing passwords. | Be cautious of fake login pages. |
| **Keylogging** | Records keystrokes secretly. | Use trusted devices and MFA. |

---

## 🧩 Best Practices for Strong Passwords

- Use **at least 12–16 characters** in each password.  
- Combine **uppercase, lowercase, numbers, and symbols**.  
- Avoid personal data (name, DOB, pet names, etc.).  
- Use **unique passwords** for every account.  
- Enable **Multi-Factor Authentication (MFA)** wherever possible.  
- Consider using a **password manager** for secure storage.

---

## 🏁 Conclusion

Through this practical exercise, I learned how password strength depends on its **length, complexity, and randomness**.  
By testing multiple passwords in **Kali Linux using PasswordMeter.com**, I understood how small improvements (like adding symbols or increasing length) drastically enhance security.  
This task reinforced the importance of using **strong, unique passwords** and **multi-factor authentication** to protect against common cyberattacks.

---

## 📸 Screenshots

### 1️⃣ Weak Password Test (`password123`)
![Weak Password Test](screenshots/1_weak_password.png)

### 2️⃣ Medium Password Test (`P@ssword123`)
![Medium Password Test](screenshots/2_medium_password.png)

### 3️⃣ Strong Password Test (`P@55w0rd!2025`)
![Strong Password Test](screenshots/3_strong_password.png)

### 4️⃣ Very Strong Password Test (`Sru$hti_D@ve!2025`)
![Very Strong Password Test](screenshots/4_very_strong_password.png)

### 5️⃣ Maximum Strength Password Test (`Sru$hti_D@ve!2025#Cyber@Security`)
![Maximum Strength Password Test](screenshots/5_max_strength_password.png)

---
