# SOC Analyst L1 Project – Nmap Network Scanning & Risk Analysis

## 📌 Project Overview
This project demonstrates hands-on network reconnaissance using Nmap to identify
open ports and running services on a target system. The goal is to analyze the
attack surface and assess security risks from a SOC Analyst L1 perspective.

---

## 🎯 Objective
- Identify open TCP ports on the target system
- Detect exposed and legacy services
- Analyze security risks caused by insecure services
- Understand attacker reconnaissance techniques

---

## 🛠️ Tools & Environment## 📊 Findings
The target system exposed multiple high-risk services such as FTP, Telnet,
and SMB. Legacy services like rlogin and remote shell were also detected,
indicating a highly insecure configuration and increased attack surface.

- Kali Linux
- Nmap 7.92## 📊 Findings
The target system exposed multiple high-risk services such as FTP, Telnet,
and SMB. Legacy services like rlogin and remote shell were also detected,
indicating a highly insecure configuration and increased attack surface.

- Target IP: 192.168.1.xx

---

## 🔍 Scan Methodology
A SYN (stealth) scan was performed to identify open TCP ports without completing
full TCP handshakes, simulating common attacker reconnaissance behavior.

### Command Used
```bash
nmap -sS 192.168.1.xx

#  📊 Findings

Nmap SYN scan revealed multiple open ports including FTP, Telnet, SMB,
and legacy remote services. These services significantly increase the
attack surface and pose high security risks if not properly secured.



The target system exposed multiple high-risk services such as FTP, Telnet,
and SMB. Legacy services like rlogin and remote shell were also detected,
indicating a highly insecure configuration and increased attack surface.

