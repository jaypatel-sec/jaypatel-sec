# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India | 🎯 Penetration Tester — January 2027 | eJPT → CPTS → OSCP → eWPTX → CPSA → CRT

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 11 |
| HTB Machines (documented) | 31 |
| CPTS Modules Completed | 14 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Inception](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Inception.md) | HackTheBox | Hard | dompdf v0.6.0 LFI (EDB-33004) → php://filter file read → Apache config enumeration → WebDAV md5crypt crack (babygurl69) → PHP webshell upload → wp-config DB cred → Squid proxy SSH pivot (cobb) → sudo su (container root) → static nmap → FTP anon crontab read → TFTP APT Pre-Invoke RCE → host root |
| [Analytics](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Analytics.md) | HackTheBox | Easy | CVE-2023-38646 Metabase Pre-Auth RCE via setup-token abuse → Docker container shell → printenv credential leak → SSH as metalytics → GameOver(lay) CVE-2023-2640/CVE-2023-32629 OverlayFS LPE → root |
| [Keeper](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Keeper.md) | HackTheBox | Easy | Request Tracker default credentials → plaintext lnorgaard password in user comments → SSH foothold → KeePass memory dump CVE-2023-32784 → PuTTY private key conversion → root SSH |
| [Delivery](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Delivery.md) | HackTheBox | Easy | TicketTrick osTicket email alias → MatterMost Internal channel cred leak → SSH as maildeliverer → CVE-2021-4034 PwnKit pkexec → root (Path 2: config.json MySQL creds → bcrypt hash → hashcat best64 wordlist → john crack → su root) |
| [Fuse](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Fuse.md) | HackTheBox | Medium | PaperCut print logs username harvest → Fabricorp01 password spray → kpasswd reset → RPC printer description credential leak → WinRM as svc-print → SeLoadDriverPrivilege + Capcom.sys SYSTEM |

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
| INE ICCA (Certified Cloud Associate) | INE | ✅ Completed |
| eJPT (eLearnSecurity Junior Penetration Tester) | INE / eLearnSecurity | ✅ Completed |
| HTB CPTS (Certified Penetration Testing Specialist) | HackTheBox | 🔄 In Progress |
| OSCP (Offensive Security Certified Professional) | OffSec | ⏳ Upcoming |
| eWPTX (Web Application Penetration Tester eXtreme) | INE / eLearnSecurity | ⏳ Upcoming |
| CPSA (CREST Practitioner Security Analyst) | CREST | ⏳ Upcoming |
| CRT (CREST Registered Tester) | CREST | ⏳ Upcoming |
| AZ-900 (Azure Fundamentals) | Microsoft | ⏳ Upcoming |

---

## Focus Areas

- Network and service enumeration — full port scanning, version detection, NSE scripting
- Exploitation — web applications, misconfigured services, CVE-based attacks
- Privilege escalation — Linux (SUID, cron, group abuse) and Windows (token abuse, service misconfigs, UAC bypass)
- Active Directory — full kill chain from credential capture to DCSync
- Penetration testing documentation — methodology, findings, and remediation
