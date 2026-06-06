# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India | 🎯 Penetration Tester — January 2027 | eJPT → CPTS → OSCP

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 11 |
| HTB Machines (documented) | 23 |
| CPTS Modules Completed | 11 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Bastion](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Bastion.md) | HackTheBox | Easy | Anonymous SMB → VHD mount (guestmount) → SAM/SYSTEM offline secretsdump → NTLM crack → SSH as L4mpje → mRemoteNG confCons.xml decrypt → SSH as Administrator |
| [Alfred](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/Alfred.md) | TryHackMe | Easy | Default credentials (admin:admin) → Jenkins Groovy Script Console RCE → Meterpreter → process migration to SYSTEM svchost.exe → Incognito token impersonation |
| [Bastard](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Bastard.md) | HackTheBox | Medium | Drupal 7.54 CVE-2018-7600 (Drupalgeddon2) form cache poisoning → RCE as iusr → SeImpersonatePrivilege → Juicy Potato SYSTEM |
| [Arctic](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Arctic.md) | HackTheBox | Easy | ColdFusion 8.0.1 FCKeditor CVE-2009-2265 arbitrary file upload → JSP web shell → reverse shell as tolis → SeImpersonatePrivilege → Juicy Potato SYSTEM |
| [Steel Mountain](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/Steel-Mountain.md) | TryHackMe | Medium | Rejetto HFS 2.3 CVE-2014-6287 (39161.py) → reverse shell as bill → PowerUp.ps1 unquoted service path (AdvancedSystemCareService9) → sc restart → SYSTEM |

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
