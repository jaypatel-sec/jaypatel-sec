# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India &nbsp;|&nbsp; 🎯 Penetration Tester — January 2027 &nbsp;|&nbsp; eJPT → CPTS → OSCP

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 9 |
| HTB Machines (documented) | 15 |
| CPTS Modules Completed | 11 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Nineveh](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Nineveh.md) | HackTheBox | Medium | phpLiteAdmin SQLite injection + LFI RCE → RSA key appended to PNG → port knocking → SSH as amrois → chkrootkit 0.49 /tmp/update cron LPE |
| [Traverxec](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Traverxec.md) | HackTheBox | Easy | Nostromo 1.9.6 CVE-2019-16278 path traversal RCE → nhttpd.conf homedirs → backup SSH key → ssh2john passphrase crack → sudo journalctl pager escape (stty rows 2) |
| [SolidState](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/SolidState.md) | HackTheBox | Medium | Apache James 2.3.2 default creds (root:root) → POP3 inbox harvest → SSH as mindy → rbash escape (ssh -t sh) → PwnKit CVE-2021-4034 |
| [Irked](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Linux/Irked.md) | HackTheBox | Easy | UnrealIRCd 3.2.8.1 backdoor CVE-2010-2075 (echo + netcat) → steghide hidden SSH creds → PwnKit CVE-2021-4034 (32-bit static compile) |
| [TomGhost](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/TomGhost.md) | TryHackMe | Easy | GhostCat CVE-2020-1938 AJP file read → web.xml credentials → SSH → GPG crack → sudo zip GTFOBins root |

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