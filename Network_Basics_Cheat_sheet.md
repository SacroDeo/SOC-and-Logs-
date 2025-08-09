# Network Basics Cheat sheet

## 📌 Common Ports & Services

| Port | Protocol | Service / Description |
|------|----------|------------------------|
| 20   | TCP      | FTP (Data) – Transfers the file data |
| 21   | TCP      | FTP (Control) – Sends commands for FTP |
| 22   | TCP/UDP  | SSH – Secure way to control another computer |
| 23   | TCP/UDP  | Telnet – Remote control without encryption |
| 25   | TCP      | SMTP – Sends emails |
| 53   | TCP/UDP  | DNS – Changes domain names to IP addresses |
| 67   | UDP      | DHCP – Server gives IP addresses |
| 68   | UDP      | DHCP – Client gets IP address |
| 69   | UDP      | TFTP – Simple file transfer |
| 80   | TCP      | HTTP – Web traffic without encryption |
| 110  | TCP      | POP3 – Gets emails from server |
| 143  | TCP      | IMAP – Reads emails from server |
| 161  | UDP      | SNMP – Manages network devices |
| 162  | UDP      | SNMP Trap – Alerts from devices |
| 443  | TCP      | HTTPS – Secure web traffic |
| 445  | TCP      | SMB – Shares files and printers |
| 3389 | TCP      | RDP – Remote desktop control |
| 8080 | TCP      | HTTP Alternate – Often for proxies or test web servers |

---

## 🗂 OSI Model Overview

<img width="800" height="618" alt="image" src="https://github.com/user-attachments/assets/1a4ade2a-dbd1-41ff-9f45-4c6d0d6db936" />







---

## 🔍 Why Study the OSI Model?

We use the **TCP/IP model** in real networks, but the **OSI model** is still important because:

- It is a **common guide** to understand networking.
- It helps to **find and fix problems** step-by-step.
- It gives **clear terms** for all network engineers.
- It shows the **big picture** of how data moves.

OSI is like a **blueprint**, TCP/IP is the **actual system** we use.

---

## 📊 OSI vs TCP/IP Mapping

| OSI Layer               | TCP/IP Equivalent |
|-------------------------|-------------------|
| 7. Application          | Application       |
| 6. Presentation         | Application       |
| 5. Session              | Application       |
| 4. Transport            | Transport         |
| 3. Network              | Internet          |
| 2. Data Link            | Network Access    |
| 1. Physical             | Network Access    |

---
**Tip:** To remember the OSI layers, use:  
**"All People Seem To Need Data Processing"** (Application → Physical).


