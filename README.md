 <div align="center">
  <img src="./assets/hero-banner.png" alt="Harikrishnan | Aspiring SOC Analyst | Blue Team | Detection Engineering" width="100%" />
</div>

<br/>

<p align="center">
  <a href="#about-me">About</a> •
  <a href="#current-focus">Current Focus</a> •
  <a href="#technical-skills">Skills</a> •
  <a href="#featured-projects">Projects</a> •
  <a href="#technical-writing">Writing</a> •
  <a href="#certifications--professional-training">Certifications</a> •
  <a href="#connect-with-me">Contact</a>
</p>

## About Me

I'm an aspiring **SOC Analyst** focused on Blue Team operations, Detection Engineering, Threat Hunting, and Incident Response.

I enjoy building hands-on security labs, simulating real-world attack techniques, analyzing security telemetry, and developing detections that turn raw events into actionable security insights.

My approach is simple: **Build things. Break things. Understand them.**

Currently expanding my knowledge of SIEM operations, Windows and Active Directory security, MITRE ATT&CK, and security automation.

<p align="center">
  <strong>Blue Team | Detection Engineering | Threat Hunting | Incident Response</strong>
</p>

---

## Cybersecurity Portfolio at a Glance

<p align="center">
  <img src="https://img.shields.io/badge/Detection%20Rules-42%20Validated-1F6FEB?style=for-the-badge" alt="42 Validated Detection Rules" />
  <img src="https://img.shields.io/badge/IR%20Playbooks-7-238636?style=for-the-badge" alt="7 Incident Response Playbooks" />
  <img src="https://img.shields.io/badge/SOC%20Dashboards-7-8957E5?style=for-the-badge" alt="7 SOC Dashboards" />
  <img src="https://img.shields.io/badge/Featured%20Projects-4-0D9488?style=for-the-badge" alt="4 Featured Projects" />
  <img src="https://img.shields.io/badge/Technical%20Writeups-5-0969DA?style=for-the-badge" alt="5 Technical Writeups" />
  <img src="https://img.shields.io/badge/Credentials-20%2B-F0883E?style=for-the-badge" alt="20+ Credentials" />
</p>

---

## Current Focus

- **Advanced Detection Engineering:** Building advanced detection logic, improving detection coverage, and validating detections against real-world attack techniques.
- **AI-Aided SOC:** Exploring AI-driven security operations, intelligent alert analysis, investigation assistance, and automated threat detection.
- **Digital Forensics & Incident Response (DFIR):** Developing skills in digital evidence collection, forensic analysis, incident investigation, and response.
- **Threat Hunting:** Proactively identifying suspicious activity, investigating threat behaviours, and uncovering hidden threats through security telemetry.
- **Security Automation:** Developing automated security workflows, alert enrichment, orchestration, and incident response processes.
- **Purple Teaming:** Bridging offensive and defensive security through adversary emulation, attack simulation, detection validation, and collaborative security testing.

---

## Technical Skills

| Category | Technologies & Tools |
|---|---|
| **SIEM & Security Monitoring** | Wazuh, Splunk |
| **Endpoint Security & Telemetry** | Sysmon, Windows Event Logs, LimaCharlie |
| **Network Security & Monitoring** | Suricata, Network Traffic Analysis |
| **Active Directory Security** | Active Directory, BloodHound, Impacket, NetExec |
| **Detection Engineering** | Custom Wazuh Rules, MITRE ATT&CK, Detection Validation |
| **Threat Hunting & Investigation** | Log Analysis, Event Correlation, Alert Triage, Threat Hunting |
| **SOAR & Case Management** | Shuffle, Tines, TheHive |
| **Security Automation & Scripting** | n8n, Python, PowerShell, Bash |
| **Incident Response & Communication** | Incident Investigation, Containment, Eradication, Recovery, Slack |
| **Security Visualization** | Grafana |
| **Web Application Security** | ModSecurity, OWASP Core Rule Set, DVWA |
| **Operating Systems** | Windows, Windows Server, Linux, Kali Linux |

---

## Featured Projects

### 1. SOC Active Directory Detection & Incident Response Lab

[GitHub Repository](https://github.com/Harikrishnan-P97/SOC-Active-Directory-Detection-and-Response-Lab)

An end-to-end Active Directory SOC lab built to simulate adversary activity, engineer and validate security detections, investigate alerts, and execute incident response workflows in a Windows domain environment.

- Deployed a Windows Server Active Directory environment with centralized security monitoring and log analysis using Wazuh.
- Engineered, tested, and validated **42 custom Wazuh detection rules** covering authentication, credential access, privilege escalation, persistence, lateral movement, and defense evasion.
- Developed **7 SOC dashboards** to support security monitoring, threat hunting, and detection analysis.
- Created **7 incident response playbooks** covering investigation, containment, eradication, and recovery.
- Simulated adversary techniques and mapped detection scenarios to the **MITRE ATT&CK framework**, validating the detection-to-investigation-to-response workflow.

### 2. SOC Automation & Detection Engineering Lab

[GitHub Repository](https://github.com/Harikrishnan-P97/SOC-Automation-Detection-Engineering-Lab)

An integrated, end-to-end SOC simulation environment designed to replicate security monitoring and incident response operations across network, web application, and phishing attack scenarios.

- Integrated **Splunk, Suricata, and ModSecurity with OWASP CRS** for centralized security event collection, monitoring, and analysis.
- Simulated **network-level attacks, web application attacks using DVWA, and phishing campaigns using GoPhish**, with Sliver C2 supporting adversary simulation.
- Developed **10 n8n automation workflows** to automate security alert processing and incident response tasks.
- Built a functional **Grafana SOC dashboard** featuring an alert overview and alert queue to simulate real-world SOC monitoring and triage operations.
- Integrated **Slack** for security alert notifications and **LimaCharlie** for endpoint detection and isolation workflows.

The project brings together attack simulation, security telemetry, detection engineering, alert automation, and response capabilities in a unified SOC environment.

### 3. SOAR + EDR Home Lab

[GitHub Repository](https://github.com/Harikrishnan-P97/SOAR-EDR-Home-Lab)

A hands-on SOAR and EDR integration project demonstrating automated security alert triage, adversary simulation, and endpoint incident response.

- Built automated security orchestration workflows using **Tines** to process and respond to security alerts.
- Integrated **LimaCharlie EDR** for endpoint monitoring, threat detection, and host isolation.
- Simulated adversary behavior, including **credential dumping using LaZagne**, to generate security events and test the response workflow.
- Integrated **Slack and Email** for automated security notifications and incident communication.
- Explored end-to-end detection-to-response automation, including alert handling, investigation, and endpoint containment.

### 4. CliHax – Cybersecurity CLI Tool

[GitHub Repository](https://github.com/Harikrishnan-P97/clihax)

A Python-based command-line reference manager for penetration testers, designed to organize, search, manage, and quickly retrieve commonly used security tool commands without leaving the terminal.

- Developed a structured CLI application using **Python**, **Click**, and **Rich**, with interactive command management and formatted terminal output.
- Implemented command storage, editing, deletion, keyword searching, category and tag filtering, and one-step clipboard copying.
- Built a **33-command starter pack** covering reconnaissance, web security, password attacks, SMB, shells, privilege escalation, and file transfers.
- Implemented **JSON import/export**, machine-readable output, and scripting capabilities to support automation and integration with other tools.
- Added shell Tab completion for **Bash, Zsh, and Fish**, alongside cross-platform user-specific data storage.
- Implemented data safety mechanisms, including atomic file writes, backups, input validation, and audit logging for destructive operations.
- Used **Poetry** for dependency management and packaging, with **Pytest**, **Ruff**, and GitHub Actions CI for testing, code quality, and Python-version compatibility.

---

## Technical Writing

I document my hands-on cybersecurity projects, technical experiments, attack simulations, detection engineering approaches, and security research through detailed technical articles.

### Top Featured Articles

**1. [Building an Active Directory SOC Lab: Detection Engineering, Threat Hunting & Incident Response with Wazuh](https://medium.com/@harikrishnan.p097/building-an-active-directory-soc-lab-detection-engineering-threat-hunting-incident-response-6f0f6c10cafd)**

A practical walkthrough of building an Active Directory SOC environment, configuring Windows and Sysmon telemetry, developing custom Wazuh detections, and mapping security activity to MITRE ATT&CK.

**2. [Operating an Active Directory SOC Lab: Detection Validation, Investigation & Incident Response](https://medium.com/@harikrishnan.p097/operating-an-active-directory-soc-lab-detection-validation-investigation-incident-response-dd48c06fc5d8)**

An operational deep dive into validating 42 custom detections, investigating security alerts, connecting detections to incident response, and documenting seven response playbooks.

**3. [Simulating a Real Security Operations Center: An End-to-End SOC Lab Project](https://medium.com/@harikrishnan.p097/simulating-a-real-security-operations-center-an-end-to-end-soc-lab-project-41cd4542d78c)**

Explores the design of an end-to-end SOC simulation environment, bringing together security monitoring, detection engineering, threat intelligence enrichment, and analyst workflows.

**4. [I Built a Phishing Lab to Finally Understand the Cyber Kill Chain](https://medium.com/@harikrishnan.p097/i-built-a-phishing-lab-to-finally-understand-the-cyber-kill-chain-9aad7c10e8c4)**

A hands-on exploration of phishing attacks through the Cyber Kill Chain, connecting attacker actions, attack stages, and defensive visibility.

**5. [Inside My Phishing Simulation Lab: Red Team Meets Blue Team](https://medium.com/@harikrishnan.p097/inside-my-phishing-simulation-lab-red-team-meets-blue-team-05731f401bb9)**

Documents a phishing simulation lab from both offensive and defensive perspectives, covering attack simulation, telemetry generation, and detection opportunities.

<p align="center">
  <a href="https://medium.com/@harikrishnan.p097">
    <img src="https://img.shields.io/badge/Medium-Explore%20All%20Articles-12100E?style=flat-square&logo=medium&logoColor=white" alt="Explore all Medium articles" />
  </a>
</p>

---

## Certifications & Professional Training

### Professional Certifications

- **Certified Ethical Hacker (CEH v12)** – EC-Council
- **Practical Ethical Hacking (PEH)** – TCM Security

### Security Training & Completion Certificates

- **Security Analyst Level 1 (SAL1)** – TryHackMe
- **Foundations of Operationalizing MITRE ATT&CK** – AttackIQ
- **Cisco Cybersecurity Training** – Cisco
- **NDG Linux Certifications** – Cisco Networking Academy

### Technical Courses

- **Splunk: Zero to Power User** – Udemy
- **Introduction to Splunk** – Splunk
- **Using Fields in Splunk** – Splunk
- **Complete Python Bootcamp: From Zero to Hero** – Udemy

### Hands-on Learning

<p align="center">
  <a href="https://tryhackme.com/p/harikrishnan.p097">
    <img src="https://img.shields.io/badge/TryHackMe-Blue%20Team-212C42?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe Blue Team" />
  </a>
  <a href="https://tryhackme.com/p/LordNumbnuts">
    <img src="https://img.shields.io/badge/TryHackMe-Red%20Team-8B2635?style=flat-square&logo=tryhackme&logoColor=white" alt="TryHackMe Red Team" />
  </a>
</p>

### Continuous Learning

Continuously developing practical cybersecurity skills through hands-on labs, security research, attack simulations, detection engineering, and incident response exercises.

---

## Connect With Me

I'm always open to connecting with cybersecurity professionals, discussing security research, sharing knowledge, and exploring opportunities in Security Operations and Blue Teaming.

<p align="center">
  <a href="https://www.linkedin.com/in/harikrishnanp097">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:harikrishnan.p097@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" />
</a>
  <a href="https://medium.com/@harikrishnan.p097">
    <img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium" />
  </a>
  <a href="https://www.credly.com/users/harikrishnan-p.f4fb62d6">
    <img src="https://img.shields.io/badge/Credly-FF6B00?style=flat-square&logo=credly&logoColor=white" alt="Credly" />
  </a>
</p>

---

## GitHub Statistics

<p align="center">
  <img
    src="https://github-readme-stats.shion.dev/api?username=Harikrishnan-P97&theme=blue_navy&hide_border=true&include_all_commits=false&count_private=false"
    height="165"
    alt="GitHub Statistics"
  />
</p>

---

**Portfolio Website:** Coming Soon