
# Hack The Box - Walkthroughs & Writeups

Welcome to my **Hack The Box** documentation repository. This project serves as a technical journal where I document my journey through the HTB labs. Each writeup here is more than just a solution; it is a step-by-step breakdown of my analytical process, the obstacles I faced, and the exploitation techniques used.

## 🎯 Repository Objectives

The purpose of this repository is threefold:

1. **Documentation:** To maintain a clear record of the vulnerabilities discovered and exploited.
2. **Skill Demonstration:** To showcase proficiency in network scanning, web exploitation, Active Directory attacks, and privilege escalation.
3. **Community Contribution:** To provide clear, educational guides for other students of cybersecurity (following HTB's rules for Retired machines).

---

## 🛠️ Technical Toolkit

Throughout these machines, I utilize industry-standard tools and frameworks:

* **Information Gathering:** `Nmap`, `Rustscan`, `FFUF`, `Gobuster`, `WhatWeb`.
* **Exploitation:** `Metasploit`, `Burp Suite`, `Sqlmap`, `Searchsploit`, `Impacket`.
* **Active Directory:** `BloodHound`, `CrackMapExec`, `Evil-WinRM`, `Responder`.
* **Post-Exploitation:** `LinPeas`, `WinPeas`, `Mimikatz`, `Chisel` (Pivoting).

---

## 📑 Methodology

Every writeup follows a standardized **Offensive Security Lifecycle**:

### 1. Enumeration & Reconnaissance

The foundation of every attack. I identify open ports, service versions, and hidden web directories to find the initial entry point.

### 2. Vulnerability Analysis

I analyze the information gathered to identify misconfigurations, outdated software, or weak credentials that can be leveraged.

### 3. Initial Access (User)

The exploitation phase where I execute the attack (RCE, SQLi, Auth Bypass, etc.) to gain a foothold on the target system.

### 4. Privilege Escalation (Root/SYSTEM)

Once inside, I perform internal enumeration to find paths to escalate my privileges and gain full control over the machine.

---

## ⚖️ Rules of Engagement & Disclaimer

* **Retired Machines Only:** In accordance with Hack The Box's Terms of Service, I only publish writeups for **Retired** machines. No flags or solutions for active machines will ever be hosted here.
* **Educational Purpose:** This content is for educational purposes only. Unauthorized access to computer systems is illegal.



