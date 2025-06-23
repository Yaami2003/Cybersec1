# 🛡️ Cybersecurity Internship - Task 1

## 🔍 Task: Scan Your Local Network for Open Ports

### 🎯 Objective:
To perform a basic TCP SYN scan on a local network device using **Nmap** and identify open ports to understand network exposure.

---

## 🛠️ Tools Used:
- [Nmap](https://nmap.org/) (via Zenmap GUI)
- Operating System: Windows (using Zenmap)

---

## 🌐 Target Details:
- **IP Address Scanned:** `192.168.56.1`
- **Command Used:**
 ```bash
nmap -sS 192.168.56.1

## 📋 Scan Results:
| Port | State | Service |
|------|-------|---------------------|
| 135 | open | msrpc |
| 139 | open | netbios-ssn |
| 445 | open | microsoft-ds |
| 6881 | open | bittorrent-tracker |

---

## ⚠️ Security Risks:
- Ports 139 & 445: File sharing — vulnerable if misconfigured.
- Port 6881: Used for torrenting — risky if not needed.
- Action: Close unused ports or restrict with firewall.

---

## 🖼️ Screenshot:
![Scan Screenshot](https://github.com/Yaami2003/Cybersec1/blob/b288b6fa22e0392f79713efbb1e6ab4465fd2538/scan_result_screenshot.jpg)

---

## ✅ Outcome:
- Performed Nmap TCP SYN scan
- Identified open ports and security risks
- Improved network recon skills

---

### 🔗 Submission Link:
[GitHub Repo Link](https://github.com/Yaami2003/Cybersec1)
