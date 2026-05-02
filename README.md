🔐 Network Scanning & Information Gathering

📘 Cybersecurity & Ethical Hacking Project

---

👩‍💻 Author

Nandhitha V N 
🎓 2nd Year Student
📚 Cybersecurity & Ethical Hacking

---

📌 Project Overview

Network scanning is a fundamental technique in cybersecurity used to identify active devices, open ports, and services within a network.

This project demonstrates how to perform network scanning using Nmap and Zenmap to analyze a system and identify potential security risks.

---

🎯 Objectives

- 🔍 Perform network scanning
- 🌐 Identify active hosts
- 🚪 Detect open ports and services
- 💻 Identify operating system
- ⚠️ Understand security risks

---

🛠️ Tools Used

- Nmap – Network scanning and security auditing tool
- Zenmap – Graphical interface for Nmap

---

⚙️ Methodology

nmap -sV -O 192.168.1.11

Steps:

1. Identified network using "ipconfig"
2. Selected target IP: 192.168.1.11
3. Performed scan using Nmap
4. Analyzed results using Zenmap

---

📊 Results & Findings

✅ Host Status

- Target system is active (UP)

---

🖼️ Scan Output

«📌 Add your screenshot in the repo and update the file name below»

![Scan Result](scan-output.png)<img width="900" height="1600" alt="WhatsApp Image 2026-05-02 at 9 38 55 PM" src="https://github.com/user-attachments/assets/47661ec6-97ce-4cb3-be7f-ab8753826422" />


📝 Explanation

The scan results show that the system (192.168.1.11) is active.
Open ports identified include:

- 80 (HTTP) – Web service
- 135 (MSRPC) – Windows communication
- 139 (NetBIOS) – File sharing
- 445 (SMB) – Network file sharing

The system is identified as Microsoft Windows 11.

---

📋 Open Ports Summary

Port| Service| Description
80| HTTP| Web server
135| MSRPC| Windows communication
139| NetBIOS| File sharing
445| SMB| Network file sharing

---

🔍 Analysis

The system is a Windows-based machine with multiple services enabled.
Ports 139 and 445 may expose file-sharing services, which can be risky if not secured.

Port 80 indicates a web server that could be vulnerable if misconfigured.

---

⚠️ Security Implications

- 🔓 Risk of unauthorized access
- 🐞 Exploitable services
- 🌐 Exposure to network attacks

🛡️ Preventive Measures

- Disable unused ports
- Use firewall protection
- Keep system updated
- Monitor network traffic

---

🧠 Concepts Learned

- Network scanning
- TCP/IP fundamentals
- Port scanning
- Service detection
- OS fingerprinting

---

✅ Conclusion

This project demonstrates how network scanning helps identify vulnerabilities in a system.

Using Nmap and Zenmap, critical details such as open ports, services, and operating system were identified. This knowledge is essential for improving system security and preventing cyber attacks.

---

📚 References

- Nmap Official Documentation
- Cybersecurity Study Materials



---
