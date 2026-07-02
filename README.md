# 🤖 MR. ROBOT CTF Walkthrough

<p align="center">

![Platform](https://img.shields.io/badge/Platform-VulnHub-blue?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Intermediate-orange?style=for-the-badge)
![Operating System](https://img.shields.io/badge/OS-Linux-success?style=for-the-badge)
![Environment](https://img.shields.io/badge/Environment-Authorized%20Lab-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</p>

---

# 📌 Overview

This repository documents my complete walkthrough of the **MR. ROBOT Capture The Flag (CTF)** machine. The assessment was performed in a controlled and authorized lab environment to strengthen practical skills in penetration testing, Linux administration, web application security, and technical documentation.

The challenge required following a structured penetration testing methodology, beginning with reconnaissance and progressing through enumeration, authentication assessment, post-exploitation analysis, and privilege escalation until administrative access was achieved.

---

# 🎯 Objectives

✔ Perform Network Reconnaissance

✔ Identify Running Services

✔ Enumerate Web Technologies

✔ Discover Hidden Resources

✔ Assess WordPress Security

✔ Obtain Initial Access

✔ Perform Linux Enumeration

✔ Identify Privilege Escalation Opportunities

✔ Obtain Root Access

✔ Document Every Phase

---

# 🖥️ Machine Information

| Property | Value |
|-----------|-------|
| Machine | MR. ROBOT |
| Platform | VulnHub |
| Operating System | Linux |
| Category | Boot2Root |
| Difficulty | Intermediate |
| Environment | Authorized Lab |
| Attacking Machine | Kali Linux |

---

# 🔄 Penetration Testing Workflow

```text
Target Discovery
       │
       ▼
Reconnaissance
       │
       ▼
Port & Service Enumeration
       │
       ▼
Web Enumeration
       │
       ▼
Information Gathering
       │
       ▼
WordPress Assessment
       │
       ▼
Authentication Assessment
       │
       ▼
Initial Foothold
       │
       ▼
Shell Stabilization
       │
       ▼
Linux Enumeration
       │
       ▼
Privilege Escalation Analysis
       │
       ▼
Root Access
       │
       ▼
Documentation
```

---

# 🔍 Phase 1 – Reconnaissance

## Objective

Identify exposed services and understand the attack surface.

## Tool

- Nmap

## Activities

- Full TCP port scan
- Service detection
- Version detection

## Findings

| Port | Service | Status |
|------|----------|--------|
| 22 | SSH | Closed |
| 80 | HTTP | Open |
| 443 | HTTPS | Open |

---

# 🌐 Phase 2 – Web Enumeration

## Objective

Analyze the web application and discover hidden resources.

## Activities

- Browse website
- Inspect page source
- Review robots.txt
- Analyze exposed resources

## Findings

- Hidden resources discovered
- Public files identified
- Useful information gathered for further assessment

---

# 📝 Phase 3 – Information Gathering

## Objective

Collect information useful for understanding the target.

## Safe Linux Commands Used

```bash
pwd
```

Display current working directory.

```bash
ls
```

List directory contents.

```bash
ls -la
```

Display hidden files.

```bash
cd
```

Navigate directories.

```bash
cat
```

View file contents.

```bash
hostname
```

Display system hostname.

```bash
whoami
```

Display current user.

```bash
id
```

Display user information.

```bash
uname -a
```

Display kernel information.

```bash
find
```

Search for files across the filesystem.

---

# 🌍 Phase 4 – WordPress Assessment

## Objective

Assess the CMS installation.

## Tool

- WPScan

## Assessment Included

- CMS Detection
- User Enumeration
- Plugin Enumeration
- Theme Enumeration
- Version Identification

---

# 🐧 Phase 5 – Linux Enumeration

## Objective

Gather local system information.

## Enumeration Areas

- Current User
- Running Services
- File Permissions
- Installed Applications
- SUID Binaries
- Environment Variables
- System Configuration
- User Accounts

---

# ⚙️ Phase 6 – Privilege Escalation Analysis

## Objective

Identify security misconfigurations.

## Checked

- File Permissions
- SUID Programs
- Writable Files
- Cron Jobs
- Scheduled Tasks
- Environment Variables
- Installed Packages
- Linux Capabilities

---

# 👑 Phase 7 – Root Access

## Result

Successfully obtained administrative privileges after identifying and validating a privilege escalation path within the authorized lab.

---

# 📷 Screenshots

Add screenshots for each phase.

```
Reconnaissance

Web Enumeration

Information Gathering

WordPress Assessment

Linux Enumeration

Privilege Escalation

Root Access
```

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|----------|
| Kali Linux | Attacking Machine |
| Nmap | Network Reconnaissance |
| WPScan | WordPress Assessment |
| Browser | Web Enumeration |
| Linux Terminal | System Enumeration |
| Bash | Shell Interaction |
| Python | Shell Management |
| Netcat | Shell Communication |
| Hydra | Password Auditing (Authorized Lab) |

---

# 📚 Skills Demonstrated

- Network Reconnaissance

- Service Enumeration

- Web Enumeration

- Information Gathering

- Linux Fundamentals

- WordPress Security

- Authentication Assessment

- Linux Enumeration

- Privilege Escalation Analysis

- Documentation

- Technical Reporting

- Capture The Flag Methodology

---

# 🧠 Learning Outcomes

Through this machine I strengthened my understanding of:

- Structured penetration testing methodology

- Network reconnaissance

- Web application assessment

- Linux system enumeration

- Security misconfiguration analysis

- Problem solving

- Documentation best practices

- Technical reporting

- Capture The Flag methodology

---

# 📈 MITRE ATT&CK (High-Level Mapping)

| Tactic |
|----------|
| Reconnaissance |
| Discovery |
| Credential Access (Assessment) |
| Initial Access |
| Execution |
| Privilege Escalation |
| Collection |

---

# 📖 References

- VulnHub

- Kali Linux Documentation

- Nmap Documentation

- WPScan Documentation

- OWASP Web Security Testing Guide

- GTFOBins (Reference)

---

# ⚠ Disclaimer

This project was completed in an **authorized Capture The Flag (CTF)** environment designed for cybersecurity education. The information contained in this repository is intended solely for learning, documentation, and professional portfolio purposes.

---

# 👨‍💻 Author

## Avinash Patil

Cybersecurity Enthusiast | Ethical Hacking | Penetration Testing | Linux | CTF Player

### Connect with me

- 💼 LinkedIn: https://linkedin.com/in/YOUR-LINK
- 💻 GitHub: https://github.com/YOUR-USERNAME

---

<p align="center">

⭐ If you found this repository informative, consider giving it a Star!

</p>
