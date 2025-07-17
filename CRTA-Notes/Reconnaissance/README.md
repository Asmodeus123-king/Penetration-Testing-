# 🔍 Reconnaissance Phase – CRTA Exam Preparation

Recon is the *first and most critical phase* of red teaming in the CRTA exam. A proper recon gives you:

- 🔎 Visibility of all live hosts & open ports  
- 📂 Enumeration of SMB shares, users, and domains  
- 🧠 Discovery of misconfigurations or weak access controls  

---

## 🎯 Objective

- Identify live systems & services
- Enumerate users, shares, and AD exposure
- Build a map for privilege escalation and lateral movement

---

## 🛠 Tools Used

| Tool            | Purpose                          |
|-----------------|----------------------------------|
| nmap          | Network & service discovery      |
| smbclient     | SMB share enumeration            |
| rpcclient     | User enumeration via RPC         |
| enum4linux    | Combined SMB/RPC/user enum       |
| crackmapexec  | Auth & config checks (SMB/WinRM) |
| ldapsearch    | AD enumeration via LDAP          |

---

## 🔎 1. Network Scan via Nmap

```bash
nmap -sC -sV -Pn -T4 -oA recon/full-scan 10.10.10.0/24
