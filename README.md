# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India &nbsp;|&nbsp; 🎯 Penetration Tester — January 2027 &nbsp;|&nbsp; eJPT → CPTS → OSCP

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 9 |
| HTB Machines (documented) | 11 |
| CPTS Modules Completed | 11 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [TomGhost](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/TomGhost.md) | TryHackMe | Easy | GhostCat CVE-2020-1938 AJP file read → web.xml credentials → SSH → GPG crack → sudo zip GTFOBins root |
| [Knife](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Knife.md) | HackTheBox | Easy | PHP 8.1.0-dev backdoor CVE-2021-39165 (User-Agentt RCE) → james reverse shell → sudo knife GTFOBins root |
| [Shocker](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Shocker.md) | HackTheBox | Easy | Shellshock CVE-2014-6271 via CGI User-Agent → shelly reverse shell → sudo perl GTFOBins root |
| [Jerry](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Jerry.md) | HackTheBox | Easy | Default Tomcat credentials (tomcat:s3cret) → WAR reverse shell deploy → NT AUTHORITY\SYSTEM |
| [Codify](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Codify.md) | HackTheBox | Easy | vm2 CVE-2023-30547 sandbox escape → SQLite bcrypt crack → bash [[ ]] pattern match bypass + pspy root cred sniff |

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
