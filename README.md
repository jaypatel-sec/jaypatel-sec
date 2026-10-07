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
| HTB Web Challenges (documented) | 6 |
| CPTS Modules Completed | 25 / 28 |
| AD Attack Chain Steps Documented | 0 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Usage](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Usage.md) | HackTheBox | Easy | Boolean-blind SQLi on /forget-password → bcrypt crack → CVE-2023-24249 Laravel Admin .jpg.php upload → reverse shell (dash) → .monitrc plaintext creds → credential reuse (xander) → 7zip @listfile symlink → root SSH key |
| [Headless](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Headless.md) | HackTheBox | Easy | Blind XSS via User-Agent header → is_admin cookie exfiltration → OS command injection in date parameter → reverse shell (dvir) → sudo syscheck relative path hijack → /tmp/initdb.sh SUID bash root |
| [Union](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Union.md) | HackTheBox | Medium | Manual UNION SQLi → MySQL FILE read → SSH unlock + credential reuse → X-Forwarded-For command injection → www-data sudo root |
| [Trick](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Trick.md) | HackTheBox | Easy | DNS AXFR → SQLi FILE privilege → LFI SSH key extraction → fail2ban actionban SUID bash |
| [Tabby](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Tabby.md) | HackTheBox | Easy | LFI → Tomcat Manager credential extraction → WAR reverse shell → CVE-2021-4034 PwnKit root |

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
