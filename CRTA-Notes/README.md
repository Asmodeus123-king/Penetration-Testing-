# 🛡 Certified Red Team Analyst (CRTA) - Exam Notes

This repository contains my structured and practical notes for the *CRTA (Certified Red Team Analyst)* certification by *CyberWarFare Labs*.

> 💥 2025 Format: 6-Hour Live, Flag-Based Exam (No Report Submission)  
> 💻 Environment: Windows Active Directory (AD), Internal Infrastructure  
> 🎯 Objective: Capture multiple user/admin flags via full red team chain

---

## 📚 What’s Inside?

This repo includes deep technical notes and commands for each stage of the red team attack lifecycle:

| Phase                     | File Name                 | Description                                                  |
|--------------------------|---------------------------|--------------------------------------------------------------|
| 🔍 Reconnaissance         | recon.md                | Network scans, SMB/RPC enum, user discovery, AD footprinting |
| 🚪 Initial Access         | initial-access.md       | Getting first shell via misconfigs or creds                  |
| 🛡 Privilege Escalation  | privilege-escalation.md | Local admin rights via Windows vulns or privesc tools        |
| 🔁 Lateral Movement       | lateral-movement.md     | Pivoting between machines using dumped creds or tokens       |
| 🏰 Domain Privesc         | domain-privesc.md       | Kerberoasting, AS-REP roasting, constrained delegation, etc. |
| 🧠 AD Enumeration         | ad-enumeration.md       | SharpHound, PowerView, LDAP tricks                           |
| 🔐 Credential Dumping     | credential-dumping.md   | Mimikatz, Rubeus, LSASS dump, secretsdump.py                 |
| ⚙ Tools Cheat Sheet      | tools-cheatsheet.md     | Fast reference for red team tools and command-line syntax    |
| 📋 Flag Tracker           | flag-tracker-template.md| Template to track each box and flag captured                 |
| 📖 Resources & Labs       | resources.md            | Practice labs, cheat sheets, and learning material           |

---

## 🧠 Why I Made This Repo

I am currently preparing for the CRTA exam (in 15 days) and using this repo to:

- Organize and revise core red team techniques
- Document working payloads and commands for AD exploitation
- Track each phase with real examples and attack paths
- Help others who are also targeting CRTA or red team roles

---

## ⚒ Tools I’m Using in My Labs

- 🐍 Impacket (wmiexec.py, psexec.py, secretsdump.py)
- 🦇 Evil-WinRM, Mimikatz, Rubeus, SharpHound
- 🪓 CrackMapExec, smbclient, ldapsearch
- 🧰 winPEAS, PowerView, BloodHound

---

## 🧪 Practice Rooms (TryHackMe)

Here are some *recommended rooms* to simulate CRTA-style skills in a real-world AD environment:

### 🔍 Reconnaissance & User Enumeration

- [Attacktive Directory](https://tryhackme.com/room/attacktivedirectory)
- [Overpass 3 - Hacked](https://tryhackme.com/room/overpass3hacked)
- [Blue](https://tryhackme.com/room/blue)
- [Relevant](https://tryhackme.com/room/relevant)
- [Ignite](https://tryhackme.com/room/ignite)

### 🛠 Initial Foothold & Exploitation

- [Retro](https://tryhackme.com/room/retro)  
- [Bounty Hacker](https://tryhackme.com/room/bountyhacker)  
- [Dogcat](https://tryhackme.com/room/dogcat)

### 🧠 Privilege Escalation (Windows Focused)

- [Windows Privesc](https://tryhackme.com/room/windows10privesc)  
- [Lian_Yu](https://tryhackme.com/room/lianyu)

### 🏹 Active Directory & Lateral Movement

- [AD Basics](https://tryhackme.com/room/activedirectorybasics)  
- [Weak RSA](https://tryhackme.com/room/weaksaucersaroom)  
- [Steel Mountain](https://tryhackme.com/room/steelmountain)

---

## 🧰 Tools Covered

- nmap, smbclient, rpcclient, enum4linux, crackmapexec
- Evil-WinRM, Rubeus, mimikatz, SharpHound, BloodHound
- PEAS, PowerView, Impacket suite, Certipy

---

## 📌 Author

Maintained by [HiHacker](https://github.com/Asmodeus123-king)

> If you find this useful, drop a ⭐ on the repo to support the project!

---

## 📎 License

This repository is for *educational purposes only*. Always practice hacking ethically and in safe, legal environments.
---
## 📂 Folder Structure
