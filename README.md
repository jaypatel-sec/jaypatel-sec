# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India | 🎯 Penetration Tester — January 2027 | eJPT → CPTS → OSCP

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 10 |
| HTB Machines (documented) | 21 |
| CPTS Modules Completed | 11 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Arctic](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Arctic.md) | HackTheBox | Easy | ColdFusion 8.0.1 FCKeditor CVE-2009-2265 arbitrary file upload → JSP web shell → reverse shell as tolis → SeImpersonatePrivilege → Juicy Potato SYSTEM |
| [Steel Mountain](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/Steel-Mountain.md) | TryHackMe | Medium | Rejetto HFS 2.3 CVE-2014-6287 (39161.py) → reverse shell as bill → PowerUp.ps1 unquoted service path (AdvancedSystemCareService9) → sc restart → SYSTEM |
| [Access](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Access.md) | HackTheBox | Easy | Anonymous FTP → backup.mdb credential extraction (mdb-tools) → Access Control.pst email (readpst) → Telnet as security → cmdkey cached Administrator credential → runas /savecred |
| [Jeeves](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Jeeves.md) | HackTheBox | Medium | Jenkins Groovy Script Console unauthenticated RCE → web_delivery Meterpreter → SeImpersonatePrivilege → MS16-075 NBNS reflection → SYSTEM token → root flag in NTFS ADS |
| [SecNotes](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/SecNotes.md) | HackTheBox | Medium | Second-Order SQLi (registration form → notes leak tyler creds) → SMB write to IIS webroot → nc.exe + PHP revshell → wsl.exe Linux root → bash_history Administrator creds |

→ [Full writeup list](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups)

---

## Portfolio Repositories

| Repository | What Is Inside | Status |
|---|---|---|
| [HTB-TryHackMe-Writeups](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups) | Full attack path writeups — enumeration through privilege escalation with exact commands and analysis | 🔄 Active |
| [HTB-Academy-CPTS-Path](https://github.com/jaypatel-sec/HTB-Academy-CPTS-Path) | All 28 CPTS modules documented with real lab output and tool breakdowns | 🔄 Active |
| [Active-Directory-Attack-Lab](https://github.com/jaypatel-sec/Active-Directory-Attack-Lab) | 9-step AD kill chain — LLMNR poisoning through DCSync in a home lab | 🔄 Active |
| [Custom-Tools](https://github.com/jaypatel-sec/Custom-Tools) | Python offensive security tools for recon, enumeration, and exploitation | ⏳ Upcoming |
| [Pentest-Reports](https://github.com/jaypatel-sec/Pentest-Reports) | Professional penetration testing reports with executive summary, CVSS scoring, and remediation | ⏳ Upcoming |

---

## Certification Roadmap

| Certification | Provider | Status |
|---|---|---|
| eJPT | INE / eLearnSecurity | 🔄 In Progress |
| HTB CPTS | HackTheBox | ⏳ Upcoming |
| OSCP | OffSec | ⏳ Upcoming |
| HTB CWES | HackTheBox | ⏳ Upcoming |
| CRTO | Zero-Point Security | ⏳ Upcoming |
| OSWE | OffSec | ⏳ Upcoming |

---

## Focus Areas

- Network and service enumeration — full port scanning, version detection, NSE scripting
- Exploitation — web applications, misconfigured services, CVE-based attacks
- Privilege escalation — Linux (SUID, cron, group abuse) and Windows
- Active Directory — full kill chain from credential capture to DCSync
- Penetration testing documentation — methodology, findings, and remediation