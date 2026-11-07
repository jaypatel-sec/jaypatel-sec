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
| HTB Web Challenges (documented) | 13 |
| CPTS Modules Completed | 25 / 28 |
| AD Attack Chain Steps Documented | 9 / 9 |

---

## 5 Most Recent Writeups

| Room / Machine | Platform | Difficulty | Key Technique |
|---|---|---|---|
| [Granny](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Granny.md) | HackTheBox | Easy | WebDAV PUT+MOVE extension bypass on IIS 6.0 (ASPX shell via `.txt` rename) → `nt authority\network service` → `SeImpersonatePrivilege` → CVE-2008-1436 Churrasco token kidnapping (RPCSS thread SYSTEM token steal) → SYSTEM |
| [Nibbles](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Nibbles.md) | HackTheBox | Easy | HTML comment path disclosure → Nibbleblog v4.0.3 → `config.xml`/`users.xml` cred inference (`admin:nibbles`) → CVE-2015-6967 My Image plugin PHP upload RCE (nibbler) → `sudo -l` world-writable `monitor.sh` → SUID bash copy → `euid=0` root |
| [Craft](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Craft.md) | HackTheBox | Medium | Gogs public repo → Python `eval()` injection via `abv` field (RCE) → Docker container root → `settings.py` MySQL creds → pymysql user table dump → Gogs login as gilfoyle (private repo) → SSH key + passphrase reuse → `.vault-token` → Vault SSH OTP root |
| [MetaTwo](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/MetaTwo.md) | HackTheBox | Easy | CVE-2022-0739 BookingPress unauthenticated SQLi → phpass crack (manager) → CVE-2021-29447 WordPress XXE via .wav (PHP 8) → wp-config.php FTP creds → send_email.php SSH creds (jnelson) → Passpie GPG key crack (blink182) → su root |
| [Soccer](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups/blob/main/HTB-Web-Challenges/Soccer.md) | HackTheBox | Easy | CVE-2021-45010 Tiny File Manager default creds + file upload RCE → Nginx vhost enumeration → blind SQLi over WebSocket (sqlmap ws://) → credential reuse (player) → doas dstat Python plugin hijack → root |

→ [Full writeup list](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups)

---

## Portfolio Repositories

| Repository | What Is Inside | Status |
|---|---|---|
| [HTB-TryHackMe-Writeups](https://github.com/jaypatel-sec/HTB-TryHackMe-Writeups) | Full attack path writeups — enumeration through privilege escalation with exact commands and analysis | 🔄 Active |
| [HTB-Academy-CPTS-Path](https://github.com/jaypatel-sec/HTB-Academy-CPTS-Path) | All 28 CPTS modules documented with real lab output and tool breakdowns | 🔄 Active |
| [Active-Directory-Attack-Lab](https://github.com/jaypatel-sec/Active-Directory-Attack-Lab) | 9-step AD kill chain — LLMNR poisoning through DCSync in a home lab | 🔄 Active |
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
