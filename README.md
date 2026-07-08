# Jay Patel — Offensive Security

Building a hands-on penetration testing portfolio with documented proof at every step.
Real labs, real output, real methodology — written to the standard of an actual engagement.

🇮🇳 India | 🎯 Penetration Tester — January 2027 | eJPT → CPTS → OSCP → CWES → CPSA → CRT

---

## What I've Built So Far

| Area | Count |
|---|---|
| TryHackMe Rooms (documented) | 11 |
| HTB Machines (documented) | 26 |
| CPTS Modules Completed | 13 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Grandpa](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Grandpa.md) | HackTheBox | Easy | IIS 6.0 WebDAV CVE-2017-7269 ScStoragePathFromUrl buffer overflow → Meterpreter as Network Service → migrate to davcdata.exe → MS14-070 tcpip.sys ioctl → NT AUTHORITY\SYSTEM |
| [Optimum](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Optimum.md) | HackTheBox | Easy | CVE-2014-6287 Rejetto HFS 2.3 null byte RCE (no auth) → Meterpreter as kostas → x86→x64 migration to explorer.exe → MS16-032 Secondary Logon race condition → NT AUTHORITY\SYSTEM |
| [Querier](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Querier.md) | HackTheBox | Medium | Anonymous SMB → XLSM VBA macro creds → MSSQL xp_dirtree NTLMv2 capture → hashcat crack → sysadmin xp_cmdshell RCE → SeImpersonatePrivilege → PrintSpoofer SYSTEM |
| [Bastion](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Machines/Windows/Bastion.md) | HackTheBox | Easy | Anonymous SMB → VHD mount (guestmount) → SAM/SYSTEM offline secretsdump → NTLM crack → SSH as L4mpje → mRemoteNG confCons.xml decrypt → SSH as Administrator |
| [Alfred](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/TryHackMe/Rooms/Alfred.md) | TryHackMe | Easy | Default credentials (admin:admin) → Jenkins Groovy Script Console RCE → Meterpreter → process migration to SYSTEM svchost.exe → Incognito token impersonation |

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
| HTB CWES (Certified Web Exploitation Specialist) | HackTheBox | ⏳ Upcoming |
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