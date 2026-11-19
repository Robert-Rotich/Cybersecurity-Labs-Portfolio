# Robert Rotich - Cybersecurity & Digital Forensics Portfolio

**Third-Year Student | Open University of Kenya (OUK)**  
**Current Role:** Aviation Security Inspector-Kenya Aiports Authority

Welcome to my cybersecurity portfolio. This repository contains detailed laboratory reports, vulnerability assessments, penetration testing write-ups, and identity management projects conducted in isolated, legal lab environments (Metasploitable 2, Kali Linux, and web application testing). 

These reports demonstrate my practical skills in network enumeration, vulnerability discovery, exploitation, remediation, and Identity and Access Management (IAM).

---

## 📂 Portfolio Contents

### 1. Network Enumeration & Information Gathering
*   **Report:** [Pentest_Metasploitable_2.pdf](01_Network_Enumeration/Pentest_Metasploitable_2.pdf)
*   **Tools Used:** `enum4linux`, `Nmap (NSE)`, `netcat`, `snmpwalk`
*   **Key Skills:** SMB/NetBIOS enumeration, identifying unauthenticated shares, banner grabbing, and analyzing legacy protocol vulnerabilities (vsftpd 2.3.4).

### 2. Vulnerability Assessment & Scanning
*   **Report:** [Openvas_Nikto_Nessus_Scan.pdf](02_Vulnerability_Assessment/Openvas_Nikto_Nessus_Scan.pdf)
*   **Tools Used:** `Nessus`, `Nikto`, `OpenVAS`, `GFI LanGuard`
*   **Key Skills:** Automated vulnerability scanning, identifying End-of-Life (EOL) software, discovering weak SSL/TLS configurations, and generating executive remediation summaries.
*   **Report:** [Mfarusi_CORS_Cookie_Test.pdf](02_Vulnerability_Assessment/Mfarusi_CORS_Cookie_Test.pdf)
*   **Key Skills:** Manual web application security testing, analyzing session cookie security flags (HttpOnly, Secure, SameSite), and verifying CSRF/CORS protections.

### 3. System Hacking & Privilege Escalation
*   **Report:** [System_Hacking_and_Privilege_Escalation.pdf](03_System_Hacking_Exploitation/System_Hacking_and_Privilege_Escalation.pdf)
*   **Tools Used:** `Netcat`, `Unshadow`, `John the Ripper`, `Nmap`
*   **Key Skills:** Extracting `/etc/shadow`, offline password cracking (MD5), and exploiting SUID misconfigurations (`/usr/bin/nmap`) to escalate from a standard user (`msfadmin`) to effective root (`euid=0`).

### 4. Identity and Access Management (IAM)
*   **Project Report:** [Link to your IAM Project PDF](04_IAM_Project/IAM_Project_Report.pdf)
*   **Tools/Concepts Used:** [e.g., Active Directory, Okta, Keycloak, OAuth 2.0, SAML, MFA implementation]
*   **Key Skills:** [e.g., Configuring Single Sign-On (SSO), enforcing Multi-Factor Authentication (MFA), implementing Role-Based Access Control (RBAC), and securing identity lifecycles.]

---

## 🛡️ Defensive & Remediation Focus
Beyond exploitation, my reports include detailed **Risk Analysis** and **Remediation Strategies**. For example, I address:
*   Mitigating cleartext protocol risks (Telnet/FTP) by enforcing SSH/SFTP.
*   Disabling anonymous SMB write access.
*   Hardening cookie configurations against Session Hijacking and XSS.
*   [Add one sentence about mitigating IAM risks, e.g., "Preventing credential stuffing through robust MFA policies."]

## 📫 Contact
*   **LinkedIn:** [Robert Rotich](https://www.linkedin.com/in/robert-rotich-6aa2b422a)
*   **Email:** robert.rotich@kaa.go.ke
