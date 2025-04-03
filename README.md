# 🔐 Penetration Testing Project

## 📋 Project Overview

This project demonstrates a full SQL Injection-based penetration testing attack using **SQLMap** against **Damn Vulnerable Web Application (DVWA)** hosted on an Ubuntu VM. The attacker system is Kali Linux, set up within a virtualized environment. The aim was to explore, exploit, and report SQL injection vulnerabilities while enhancing practical security and ethical hacking skills.

---

## 🖥️ IT Asset Inventory

### 🔧 Attacker's Application
- **Name:** Burp Suite
- **Version:** 1.8.4#stable
- **OS:** Kali Linux
- **Description:** Automated tool for identifying and exploiting SQL injection vulnerabilities.
- **Official Site:** [https://sqlmap.org](https://sqlmap.org)

### 🧪 Victim's Application
- **Name:** Buggy Web Application (BWAPP)/DVWA
- **Description:** A deliberately insecure web application for security training and testing.
- **Repo:** [https://github.com/digininja/DVWA](https://github.com/digininja/DVWA)

### 🌐 Network Configuration
- **Attacker:**  
  - OS: Kali Linux  
  - IP: `192.168.158.25`
- **Victim:**  
  - OS: Ubuntu 23.10  
  - IP Range: `192.168.158.50 - 192.168.158.60`

---

## 🛠️ Virtual Lab Setup

### 📦 Virtualization Tools
- **VirtualBox** – Used on macOS Intel.
- **UTM** – Used for Apple Silicon (M1/M2/M3).

### 💻 Hardware
Networked Virtual Machines hosted on a physical system allowing communication between attacker and victim machines.

### 🌍 Web Resources
- [https://sqlmap.org](https://sqlmap.org)  
- [https://github.com/digininja/DVWA](https://github.com/digininja/DVWA)  
- [https://www.kali.org](https://www.kali.org)  
- [https://ubuntu.com](https://ubuntu.com)  
- [YouTube Setup Tutorial](https://www.youtube.com/watch?v=WkyDxNJkgQ4)

---

## 📡 Project Execution

### 🔍 Objectives
- **Vulnerability Detection:** Identify SQL injection flaws.
- **Exploit Demonstration:** Use SQLMap to extract sensitive information.
- **Skill Development:** Apply penetration testing methodologies in a real-world simulation.

### 🔒 Security Lessons
- Web apps are highly vulnerable to SQLi without sanitization.
- Importance of proactive monitoring and regular audits.
- Use of ethical hacking tools to understand attack vectors and prevention.

---

## 🧭 Step-by-Step Setup Instructions

(For brevity, the full instruction steps from the PDF are summarized. The file includes all setup procedures for both macOS and Windows users.)

---

## 🧬 Tools Installation & Configuration

```bash
sudo apt update && sudo apt install sqlmap
