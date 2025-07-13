# Ethical Hacking & Penetration Testing Lab - Kali Linux & Metasploit

## Project Overview  
This lab simulates real-world penetration testing using Kali Linux, Metasploitable 2, and DVWA. It walks through every major stage of a cyberattack, from reconnaissance to exploitation and credential capture. Designed in VirtualBox, this hands-on project demonstrates ethical hacking, vulnerability exploitation, and web application testing in a controlled environment.

I built this project to understand and simulate attacker behavior. It helped me develop key skills in vulnerability discovery, exploit execution, and network traffic analysis. By compromising services like vsFTPd and DVWA, and capturing plaintext credentials with Wireshark, I successfully demonstrated full attack chains with real impact.

---

## Features  
-  **Reconnaissance**: Scanned 27 open ports and identified 17+ services using Nmap  
-  **FTP Exploitation**: Gained remote root access by exploiting vsFTPd 2.3.4 using Metasploit  
-  **Web Hacking**: Performed SQL Injection & XSS attacks against DVWA  
-  **Post-Exploitation**: Captured login credentials over HTTP using Wireshark  
-  **Real-World Simulation**: Offline lab setup with host-only network to simulate attacker-target isolation  
-  **Documentation**: Report supported by 9 screenshots across key stages

---

## Screenshots  
**Project Folder & Lab Setup**  
_VirtualBox with Kali Linux & Metasploitable 2 on host-only network_

**Nmap Scan Results**  
_Identified ports and vulnerable services (FTP, HTTP, MySQL, Samba, etc.)_

**Metasploit Exploit**  
_Remote shell access via vsFTPd 2.3.4 backdoor_

**DVWA SQL Injection**  
_Manual login bypass and database extraction_

**XSS Injection in DVWA**  
_Stored XSS injecting custom script in message board_

**Wireshark Capture**  
_Intercepted plaintext HTTP POST credentials_

---

## Technologies & Skills Gained

### 🛠️ Technical Skills
- Kali Linux, Metasploit, Metasploitable 2  
- Nmap, Nikto, DVWA  
- Wireshark, VirtualBox  
- Port & Service Enumeration  
- Exploit Execution (Metasploit)  
- SQL Injection & Cross-Site Scripting (XSS)  
- Host-Only Networking & Lab Isolation  
- Traffic Analysis & Credential Capture  
- Technical Documentation & Reporting

### 💡 Soft Skills
- Ethical Hacking Mindset  
- Problem Solving  
- Attention to Detail  
- Technical Communication  
- Process Documentation

---

## About  
This is an educational project for ethical hacking practice in a safe environment.  
Never use these techniques on live systems without permission.  
