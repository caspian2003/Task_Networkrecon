# Task_Networkrecon
Here’s a README.md file that you can upload along with your Nmap scan report to GitHub. It is formatted for professional and academic presentation, suitable for internship submission or portfolio showcase.


---

# 🔍 Nmap Network Reconnaissance Report

This repository contains a professional-level network reconnaissance report using **Nmap**, created as part of an internship project.

## 📘 Project Overview

The goal of this task was to perform a vulnerability assessment and gather information about a target system using Nmap. The scan revealed open ports, associated services, and potential security issues.

---

## 📁 Report Contents

- ✅ Professional PDF report of Nmap scan
- ✅ Analysis of open ports: `23`, `139`, `445`
- ✅ Scanning methodology and tools used
- ✅ Exploitation risks and mitigation strategies

---

## 🛠️ Tools Used

- **Nmap (Network Mapper)**
  - Type: Open-source network scanner
  - Use: Port scanning, service enumeration, OS detection

### Nmap Commands Used:

bash
nmap <target-ip>          # Basic TCP scan
nmap -sS <target-ip>      # Stealth SYN scan
nmap -sT <target-ip>      # Full TCP connect scan
nmap -sV <target-ip>      # Service/version detection
nmap -Pn <target-ip>      # Firewall evasion (skip ping)
nmap -O <target-ip>       # OS detection
nmap -A <target-ip>       # Aggressive scan (includes above)


---

🚪 Open Ports Identified

Port	Service	Description

23	Telnet	Unencrypted remote login service
139	NetBIOS-SSN	Windows file/printer sharing
445	Microsoft-DS	SMB over TCP, Windows file sharing



---

🔓 Exploitation Possibilities

Telnet (23): Brute-force attacks, packet sniffing

NetBIOS (139): SMB info disclosure, LLMNR poisoning

SMB (445): Exploitable via EternalBlue, SMBGhost



---

🛡️ Mitigation Recommendations

Disable Telnet, use SSH

Block NetBIOS/SMB on public interfaces

Apply latest security patches

Disable SMBv1 protocol



---

🎯 Learning Outcomes

Performed detailed Nmap scanning

Identified critical ports and vulnerabilities

Learned exploitation and defense techniques

Gained experience in professional report writing



---

📄 Report Preview

> See Nmap_Scan_Report.pdf for the full analysis and recommendations.




---

📬 Contact

For any questions or clarifications, feel free to reach out via GitHub Issues or connect on LinkedIn.


---

⭐️ Star this repo if you found it useful!

---
