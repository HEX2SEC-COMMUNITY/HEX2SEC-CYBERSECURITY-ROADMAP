<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,45:07140F,100:00FF88&height=230&section=header&text=HEX2SEC&fontSize=68&fontColor=00FF88&animation=twinkling&fontAlignY=36&desc=CYBERSECURITY%20ROADMAP&descAlignY=59&descSize=19&descColor=FFFFFF" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2600&pause=900&color=00FF88&center=true&vCenter=true&width=850&lines=%3E%3E+BOOTING+CYBERSECURITY+ROADMAP...;%3E%3E+FROM+ZERO+TO+SECURITY+RESEARCHER;%3E%3E+NETWORKING+%7C+LINUX+%7C+WEB+SECURITY;%3E%3E+PENTESTING+%7C+BUG+HUNTING+%7C+CTF;%3E%3E+LEARN.+PRACTICE.+RESEARCH.+SECURE." alt="Hex2Sec typing animation"/>

<br>

<img src="https://img.shields.io/badge/ROADMAP-OPEN-00FF88?style=for-the-badge&labelColor=050505"/>
<img src="https://img.shields.io/badge/LEVEL-BEGINNER%20%E2%86%92%20ADVANCED-00FF88?style=for-the-badge&labelColor=050505"/>
<img src="https://img.shields.io/badge/FOCUS-CYBERSECURITY-00FF88?style=for-the-badge&labelColor=050505"/>

</div>

---

# `root@hex2sec:~$ cat README.md`

Welcome to the **Hex2Sec Cybersecurity Roadmap** — a structured learning path for anyone who wants to understand cybersecurity from the fundamentals and progress toward **penetration testing, bug hunting, security research, and secure development**.

This roadmap is designed for **learning and authorized practice only**. Use the knowledge responsibly and test only systems you own or have explicit permission to assess.

> **You don't need to know everything before you start. You just need to start learning.**

---

## `root@hex2sec:~$ ./roadmap`

```text
                         ┌──────────────────────┐
                         │      HEX2SEC         │
                         │  CYBERSECURITY LAB   │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  01  FUNDAMENTALS    │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  02  NETWORKING      │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  03  LINUX & SYSTEMS │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  04  PROGRAMMING     │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  05  WEB TECHNOLOGY  │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  06  WEB SECURITY    │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  07  PENTESTING      │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  08  BUG HUNTING     │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  09  CTF & LABS      │
                         └──────────┬───────────┘
                                    │
                         ┌──────────▼───────────┐
                         │  10  RESEARCH        │
                         └──────────────────────┘
```

---

## `root@hex2sec:~$ ./01-foundations`

### 🧠 01 — Cybersecurity Fundamentals

Build the mental model before touching security tools.

- CIA Triad
- Threats, vulnerabilities & risks
- Authentication & authorization
- Security controls
- Attack surface
- Common attack types
- Security terminology
- Ethics & responsible disclosure

**Goal:** Understand what cybersecurity is and how security problems are described.

---

## `root@hex2sec:~$ ./02-networking`

### 🌐 02 — Networking

A strong network foundation is essential for penetration testing.

- OSI & TCP/IP models
- IPv4 & IPv6
- MAC addresses
- TCP & UDP
- Ports & protocols
- DNS
- DHCP
- HTTP / HTTPS
- Routing & NAT
- Firewalls
- Proxies
- VPN fundamentals
- Packet analysis

**Practice tools:** Wireshark, Nmap, tcpdump

**Goal:** Understand what happens when a client communicates with a server.

---

## `root@hex2sec:~$ ./03-linux`

### 🐧 03 — Linux & Systems

Learn to operate comfortably from the terminal.

- Linux filesystem
- Users & groups
- Permissions
- Processes
- Services
- Environment variables
- Package management
- SSH
- Bash
- Logs
- Cron
- Networking commands
- Basic system administration

**Practice:** Build a Linux virtual machine and use the terminal daily.

---

## `root@hex2sec:~$ ./04-programming`

### 💻 04 — Programming & Scripting

You do not need to become a software engineer first. Learn enough programming to understand, automate, and inspect systems.

Recommended languages:

- Python
- Bash
- JavaScript
- SQL
- C fundamentals
- Go — optional

Focus on:

```text
Variables
Functions
Conditions
Loops
Data structures
Files
HTTP requests
APIs
Regular expressions
Automation
```

**Goal:** Turn repetitive security tasks into reproducible scripts.

---

## `root@hex2sec:~$ ./05-web`

### 🌐 05 — Web Technology

Before testing web applications, understand how they work.

- HTML
- CSS
- JavaScript
- HTTP requests & responses
- Headers
- Cookies
- Sessions
- Authentication
- REST APIs
- JSON
- Databases
- SQL
- Same-Origin Policy
- CORS
- Browser fundamentals

**Practice tools:** Browser DevTools, Burp Suite

---

## `root@hex2sec:~$ ./06-web-security`

### 🛡️ 06 — Web Application Security

Study vulnerabilities in intentionally vulnerable labs before testing real applications.

Core topics:

- SQL Injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Authentication weaknesses
- Authorization / access control
- IDOR
- File upload vulnerabilities
- Path traversal
- Command injection
- Server-Side Request Forgery (SSRF)
- Server-Side Template Injection (SSTI)
- API security
- Security misconfiguration

**Reference:** OWASP Web Security resources

**Goal:** Understand the vulnerability, why it exists, how to validate it safely, and how to remediate it.

---

## `root@hex2sec:~$ ./07-pentesting`

### ⚔️ 07 — Penetration Testing

Learn the methodology, not just individual tools.

```text
RECONNAISSANCE
      ↓
ENUMERATION
      ↓
VULNERABILITY ANALYSIS
      ↓
VALIDATION
      ↓
EXPLOITATION — AUTHORIZED LABS ONLY
      ↓
POST-EXPLOITATION — AUTHORIZED LABS ONLY
      ↓
RISK ANALYSIS
      ↓
REPORTING
      ↓
REMEDIATION
      ↓
RETEST
```

Important skills:

- Scope definition
- Reconnaissance
- Enumeration
- Vulnerability validation
- Evidence collection
- Risk assessment
- Professional reporting
- Remediation advice
- Retesting

**Practice only in your own lab, CTFs, or explicitly authorized environments.**

---

## `root@hex2sec:~$ ./08-bug-hunting`

### 🐞 08 — Bug Hunting

Learn how to approach bug bounty programs professionally.

```text
PROGRAM SCOPE
      ↓
ASSET DISCOVERY
      ↓
ATTACK SURFACE MAPPING
      ↓
TESTING
      ↓
VALIDATION
      ↓
IMPACT ANALYSIS
      ↓
EVIDENCE
      ↓
RESPONSIBLE REPORT
```

Study:

- Program scope
- Reconnaissance
- Asset discovery
- Web/API testing
- Access control
- Authentication
- Business logic
- Vulnerability validation
- Impact assessment
- Responsible disclosure
- Report writing

**Golden rule:** Never test targets outside the program's authorized scope.

---

## `root@hex2sec:~$ ./09-labs`

### 🧪 09 — Labs, CTFs & Practice

Theory becomes useful when you practice.

Recommended practice environments:

- Local vulnerable applications
- Capture The Flag challenges
- Web security labs
- Networking labs
- Linux privilege labs
- API security labs
- Reverse engineering challenges

### Suggested progression

```text
BEGINNER
   ↓
Basic Linux + Networking
   ↓
Web Fundamentals
   ↓
Simple CTF Challenges
   ↓
Web Security Labs
   ↓
Intermediate CTF
   ↓
Pentesting Labs
   ↓
Advanced Research
```

---

## `root@hex2sec:~$ ./10-research`

### 🔬 10 — Security Research

Once the fundamentals are strong, start researching beyond tutorials.

Explore:

- Vulnerability analysis
- Reverse engineering
- Malware analysis
- Binary exploitation
- Network security
- Cloud security
- Mobile security
- API security
- Authentication research
- Threat intelligence
- Secure coding
- Security automation

**Goal:** Stop only following walkthroughs and start asking:

> **"Why does this work?"**

---

## `root@hex2sec:~$ ./toolkit`

### 🧰 Security Toolkit

| Category | Tools |
|---|---|
| Network | Nmap, Wireshark, tcpdump |
| Web | Burp Suite, browser DevTools |
| Linux | Bash, SSH, common Unix utilities |
| Enumeration | Gobuster, ffuf |
| Analysis | CyberChef, file/bin utilities |
| Research | Ghidra, YARA |
| Development | Python, Git, Docker |
| Practice | CTF platforms & local labs |

**Learn the concept first. Learn the tool second.**

---

## `root@hex2sec:~$ ./learning-loop`

### 🔁 The Hex2Sec Learning Loop

```text
       ┌───────────────┐
       │     LEARN     │
       └───────┬───────┘
               ↓
       ┌───────────────┐
       │    PRACTICE   │
       └───────┬───────┘
               ↓
       ┌───────────────┐
       │    RESEARCH   │
       └───────┬───────┘
               ↓
       ┌───────────────┐
       │     BUILD     │
       └───────┬───────┘
               ↓
       ┌───────────────┐
       │     SHARE     │
       └───────┬───────┘
               │
               └──────────────→ REPEAT
```

---

## `root@hex2sec:~$ cat ethics.txt`

### ⚠️ Responsible Security

Hex2Sec promotes **ethical and responsible cybersecurity learning**.

Always:

- Practice on systems you own.
- Use intentionally vulnerable labs.
- Follow CTF rules.
- Respect bug bounty scope.
- Obtain permission before testing.
- Protect sensitive information.
- Report vulnerabilities responsibly.
- Never use security knowledge to harm others.

```text
AUTHORIZED  →  LEARN
AUTHORIZED  →  TEST
AUTHORIZED  →  RESEARCH
AUTHORIZED  →  REPORT

UNAUTHORIZED → STOP
```

---

## `root@hex2sec:~$ ./progress`

### 📈 Progress Checklist

- [ ] Cybersecurity fundamentals
- [ ] Networking fundamentals
- [ ] Linux fundamentals
- [ ] Bash basics
- [ ] Python basics
- [ ] Git & GitHub
- [ ] HTTP / HTTPS
- [ ] Web fundamentals
- [ ] SQL fundamentals
- [ ] Browser DevTools
- [ ] Burp Suite fundamentals
- [ ] OWASP Web Security
- [ ] Basic CTFs
- [ ] Web security labs
- [ ] Recon methodology
- [ ] Pentesting methodology
- [ ] Vulnerability reporting
- [ ] Bug bounty methodology
- [ ] Security research

---

## `root@hex2sec:~$ ./contribute`

### 🤝 Contributing

Hex2Sec is built around community learning.

You can contribute by:

- Improving explanations
- Adding beginner-friendly resources
- Creating legal practice labs
- Sharing write-ups
- Fixing documentation
- Translating learning materials
- Suggesting roadmap improvements

Pull requests and constructive discussions are welcome.

---

<div align="center">

### `LEARN • PRACTICE • RESEARCH • BUILD • SECURE`

<br>

<img src="https://img.shields.io/badge/HEX2SEC-CYBERSECURITY%20ROADMAP-00FF88?style=for-the-badge&labelColor=050505"/>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF88,50:07140F,100:050505&height=130&section=footer" width="100%"/>

</div>
