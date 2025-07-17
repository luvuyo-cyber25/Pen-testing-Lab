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
### Lab Setup
![Lab Setup](Lab%20Setup.png)
Virtual environment with Kali Linux and Metasploitable2 running in VirtualBox

### Nmap Scan - Initial Results
![Nmap Scan Results 1](Nmap%20Scan%20Results%201.png)
Nmap scanning reveals open ports and services running on Metasploitable2

### Nmap Scan - Service Details
![Nmap Scan Results 2](Nmap%20Scan%20Results%202.png)
More detailed enumeration of services (e.g., Apache, MySQL, VSFTPD).

### Metasploit Exploit - Discovery Phase
![Metasploit Exploit 1](Metasploit%20Exploit%201.png)
Used Metasploit to find and prepare an exploit for a vulnerable service..

### Metasploit Exploit - Shell Access
![Metasploit Exploit 2](Metasploit%20Exploit%202.png)
Successfully gained reverse shell access to Metasploitable2 using an exploit.

### SQL Injection on DVWA
![DVWA SQL Injection](DVWA%20SQL%20Injection.png)
Performed SQL Injection attack via DVWA to extract database info.

### XSS Injection on DVWA
![XSS Injection on DVWA](XSS%20injection%20on%20DVWA.png)
Injected malicious script into DVWA's comment field, triggering a JavaScript alert

### Wireshark Capture
![Wireshark Capture](Wireshark%20Capture.png)
Captured and analyzed network packets using Wireshark.

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
