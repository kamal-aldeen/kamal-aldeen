# 🛡️ SOC Analyst Journey

## 👨‍💻 About Me
I am a cybersecurity learner focused on becoming a SOC (Security Operations Center) Analyst.  
I am building my skills through hands-on practice by analyzing real-world alerts, investigating logs, and understanding attack patterns.

---

## 🎯 Objective
My goal is to gain practical experience in:
- Log Analysis
- Incident Response
- Threat Detection
- Security Monitoring

---

## 🧠 Skills
- Log Analysis (Windows Event Logs)
- SIEM Basics
- Networking Fundamentals
- Incident Investigation
- Threat Intelligence (basic usage)
- Linux & Windows Basics

---

## 🛠️ Tools & Platforms
- LetsDefend
- Event Viewer (Windows)
- VirusTotal
- Linux VM
- Browser-based investigation

---

## 🔍 Sample Case Analysis

### 🚨 Case: Brute Force Attack (RDP)

**Scenario:**
Multiple failed login attempts followed by a successful login from an external IP address.

**Findings:**
- Event ID 4625 → Failed logins
- Event ID 4624 → Successful login
- Logon Type 10 → Remote Interactive (RDP)
- Source IP: Suspicious external address

**Analysis:**
The attacker attempted multiple logins using different credentials (brute force).  
Eventually, a valid account was compromised.

**Conclusion:**
🔴 Malicious Activity (Confirmed Compromise)

---

## 📁 Repository Structure
