# Honeyuser-Login-System
Developed a Honeyuser Login System using Python that integrates deception-based security into authentication. The system uses fake user accounts (honeyusers) to detect unauthorized login attempts, log attacker details such as IP and timestamp, and alert administrators for early threat detection.

##  Objective

The Honeyuser Login System is a cybersecurity-focused project designed to enhance traditional authentication mechanisms using deception-based security. The objective is to detect unauthorized access attempts by introducing decoy user accounts (honeyusers) that act as traps for attackers.

The system logs suspicious login attempts, generates alerts, and helps in early detection of threats such as brute-force attacks, credential stuffing, and insider misuse.

---

##  Skills Learned

- Understanding of authentication security mechanisms  
- Knowledge of deception-based security (honeytokens)  
- Log analysis and intrusion detection concepts  
- Secure password handling (hashing techniques)  
- Database design and access control  
- Cyber threat detection and monitoring  

---

##  Tools & Technologies Used

- **Python** – Backend logic and scripting  
- **Flask / Django** – Web framework  
- **SQLite / MySQL** – Database management  
- **bcrypt / hashlib** – Password hashing  
- **HTML, CSS, Bootstrap** – Frontend interface  
- **Logging Module** – Monitoring login attempts  
- **SMTP / API Alerts** – Notification system  

---

##  Key Features

- 🔐 Secure User Authentication System  
- 🍯 Honeyuser (Decoy Account) Detection  
- 📊 Real-time Login Monitoring  
- 🚨 Alert Generation for Suspicious Activity  
- 📝 Logging of IP Address & Timestamp  
- 🛡️ Protection against Brute-force Attacks  

---

## 🔄 System Workflow

1. User enters login credentials  
2. System checks if account is real or honeyuser  
3. If honeyuser → trigger alert 🚨  
4. If valid user → authenticate and grant access  
5. All attempts are logged for analysis  

---

## 📸 Screenshots

Example:

![Login Page](https://github.com/Point-ww3/Honeyuser-Login-System/blob/main/Screenshot%202026-04-09%20123914.png)
![Dashboard](https://github.com/Point-ww3/Honeyuser-Login-System/blob/main/Screenshot%202026-04-09%20130809.png)

---

##  Project Outcome

This project demonstrates how deception techniques can be used to strengthen cybersecurity defenses. It provides early threat detection and improves system visibility against unauthorized access attempts.

---

##  Future Enhancements

- Multi-Factor Authentication (MFA)  
- Integration with SIEM tools  
- Advanced threat analytics  
- Real-time dashboard monitoring  
- AI-based anomaly detection  
