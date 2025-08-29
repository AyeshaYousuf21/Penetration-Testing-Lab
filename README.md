#  Penetration Testing of Web Applications and Vulnerable Systems  

## Overview  
This project demonstrates a **penetration testing (PT) lab environment** focused on identifying and exploiting vulnerabilities in intentionally vulnerable systems and web applications. The objective was to apply all phases of the penetration testing methodology while gaining hands-on experience with real-world attack scenarios.  

---

##  Target Systems  
The following vulnerable machines were used in this project:  
- **bWAPP (Buggy Web Application Project)** – Web application with 100+ vulnerabilities  
- **DVWA (Damn Vulnerable Web Application)** – PHP/MySQL-based application for practicing OWASP Top 10  
- **DIVA (Damn Insecure and Vulnerable App)** – Android application for mobile security testing  
- **Metasploitable 2** – Intentionally vulnerable Linux system for exploit practice  

---

##  Penetration Testing Phases Followed  
The project was conducted using the standard **Penetration Testing Lifecycle**:  

1. **Information Gathering (Reconnaissance)**  
   - Identified open ports, services, and application entry points  
   - Used tools like `nmap`, `whois`, and manual inspection  

2. **Scanning & Enumeration**  
   - Performed service enumeration and vulnerability scanning  
   - Tools: `nmap NSE scripts`, `nikto`, `dirb`  

3. **Exploitation**  
   - Exploited vulnerabilities in each machine, such as:  
     - **SQL Injection** (DVWA, bWAPP)  
     - **XSS (Cross-Site Scripting)** (DVWA, bWAPP)  
     - **Command Injection** (DVWA, Metasploitable2)  
     - **Weak Authentication & Bruteforce** (DVWA, Metasploitable2)  
     - **Android App Vulnerabilities** (DIVA)  

4. **Post-Exploitation**  
   - Gained system access, retrieved sensitive data, and escalated privileges where possible  

5. **Reporting**  
   - Documented vulnerabilities, exploits, and mitigation strategies  

---

##  Key Outcomes  
- Successfully exploited vulnerabilities on all four machines  
- Demonstrated **OWASP Top 10 attacks** (XSS, SQLi, Command Injection, Broken Auth, etc.)  
- Practiced **system-level exploitation** using Metasploitable 2  
- Gained practical skills in **end-to-end penetration testing methodology**  

---

##  Conclusion  
This project highlights the importance of **penetration testing for web applications and systems** by simulating real-world attacks in a controlled lab environment. By exploiting vulnerabilities across multiple platforms, this project demonstrates how attackers can compromise systems and why **secure coding practices and system hardening** are critical.  

---
