# Dorathy Christopher | DFIR Analyst

Hello, I’m Dorathy. I am a detail-oriented Cybersecurity Analyst focused on protecting digital infrastructures. My passion is in digital forensics and incident response, from investigating malware and phishing to building tools that make investigations faster and more effective.

I enjoy turning investigations into clear case studies that show not just the process, but the results. This GitHub is a portfolio of my hands-on security projects, each one designed to reflect real-world challenges and how I approach solving them.





## Tools and Techniques I Use

**Forensics:** Autopsy, FTK Imager, Volatility, Velociraptor

**SOC/Monitoring:** Splunk, Wireshark, Wazuh

**Cloud Security:** AWS CloudTrail, IAM, GuardDuty

**Threat Intelligence:** MITRE ATT&CK, YARA, OSINT

**Programming & Automation:** Python, PowerShell, Bash


## Featured Projects

Here are some highlights of my hands-on work, demonstrating my analytical process and technical skills.

### DOSINT - Custom OSINT & Forensics Automation Tool
To streamline investigations, I developed **DOSINT**, a command-line tool designed to be a force multiplier for analysts. Written in Python, it automates tedious reconnaissance tasks by integrating OSINT, local file forensics, and CTF utilities into a single, cohesive toolkit. Its Intelligent Pivot Engine automatically discovers new leads during scans and allows for immediate action on them. This project showcases my ability to identify operational pain points and build practical tools to solve them.
*   **Key Skills:** `Python`, `Tool Development`, `Automation`, `OSINT`, `API Integration`, `Forensics`
*   **[Explore the Tool on GitHub](https://github.com/Dorakhris/dosint)**

### Strategic Threat Intelligence Analysis for a Professional Services Firm
I conduct a comprehensive analysis of the cyber threat landscape targeting a major professional services firm (Deloitte). The goal was to identify the most potent threat actors, analyze their TTPs, and provide a strategic roadmap for leadership to mitigate current and future risks.
*   **Key Skills:** `Threat Intelligence`, `MITRE ATT&CK`, `NIST 800-53`, `OPENCTI`
*   **[View the Full Incident Report Here](https://github.com/Dorakhris/Strategic-Threat-Intelligence-Analysis-for-a-Professional-Services-Firm)**

### Azure Cloud Security Engineering: A Defense-in-Depth Implementation
This project demonstrates the implementation of a comprehensive, multi-layered security architecture within Microsoft Azure. Following the Defense-in-Depth strategy, I established security controls across nine distinct areas, including identity management, network segmentation, container security, and automated threat response. The goal was to build a resilient environment capable of protecting sensitive data while providing full visibility and automated mitigation of security threats.
*   **Key Skills:** `Cloud Security`, `Azure`, `Incident Response`, `Microsoft Sentinel`, `IAM`, `JIT`
*   **[View the Full Incident Report Here][(https://github.com/Dorakhris/Azure-Cloud-Security-Engineering-A-Defense-in-Depth-Implementation)]**
  
### AWS Incident Response: Investigating a Compromised IAM User
I designed and executed a full-cycle cloud incident response exercise in AWS, acting as both the attacker and defender. I simulated a breach using a compromised IAM user (KeyHunter) to enumerate and access a sensitive S3 bucket. Then, as the responding analyst, I used **AWS CloudTrail** to trace the attacker's TTPs, from initial login to S3 discovery. This project demonstrates my end-to-end experience in detecting and remediating threats within a modern cloud environment.
*   **Key Skills:** `Cloud Security`, `AWS`, `Incident Response`, `CloudTrail`, `IAM`, `S3`
*   **[View the Full Incident Report Here](https://github.com/Dorakhris/AWS-Incident-Response-Investigating-a-Compromised-IAM-User)**

### Memory Forensics Investigation of Cridex Malware
I investigated a workstation with anomalous network traffic that evaded traditional AV scans. By performing a meticulous memory forensics analysis with **Volatility**, I bypassed the attacker's stealth techniques to uncover a Cridex banking trojan hiding inside a legitimate Windows process. My investigation revealed its entire operational playbook—from process injection to its live C2 channels—and its ultimate goal of intercepting encrypted financial data.
*   **Key Skills:** `Memory Forensics`, `Malware Analysis`, `Volatility`, `Live System Analysis`, `Network Forensics`
*   **[See the Analysis and Playbook Here](https://github.com/Dorakhris/Memory-Forensics-Investigation-of-Cridex-Malware/blob/main/README.md)**

### Forensic Investigation of a Spear-Phishing Incident
I was brought in as the lead forensic investigator for a high-stakes incident where executive statements conflicted. By performing a deep analysis of email headers from a forensic disk image, I proved a sensitive file leak was caused by a sophisticated spoof from an external attacker, not an insider threat. This investigation resolved the internal dispute with definitive digital evidence and identified the true source of the breach.
*   **Key Skills:** `Digital Forensics`, `Email Forensics`, `FTK Imager`, `Incident Response`, `Social Engineering Analysis`
*   **[View the Full Forensic Report Here](https://github.com/Dorakhris/Spear-Phishing-Forensics-Case/blob/main/Spear-Phishing-Forensics-Case/README.md)**

### Network Forensic Analysis of C2 Infrastructure
I performed a deep-dive network analysis of a `.pcap` file using **Wireshark** to identify a cluster of C2 servers. By triaging conversations by packet count and validating IPs with VirusTotal, I uncovered the attacker's full communication infrastructure.
*   **Key Skills:** `Network Forensics`, `Wireshark`, `Incident Response`, `Threat Intelligence`
*   **[View the Analysis Here](https://github.com/Dorakhris/Network-Forensic-Analysis)**

### Incident Handler's Journal: A Multi-Scenario Response
I documented my response across three distinct scenarios: a live ransomware attack, a data extortion attempt, and a proactive vulnerability assessment. This journal showcases my ability to manage the full incident lifecycle while aligning actions with compliance needs like HIPAA and PCI DSS.
*   **Key Skills:** `Incident Response`, `SOC Operations`, `Splunk`, `Ransomware`, `Forensics`
*   **[Explore the Journal Entries Here](https://github.com/Dorakhris/Incident-Journal)**

### Digital Forensics Case: The Stolen Szechuan Sauce
I conducted a classic disk forensic investigation using **Autopsy** to solve a data theft case. My analysis involved recovering deleted artifacts, reviewing logs, and building a complete attack timeline which I mapped to the MITRE ATT&CK framework.
*   **Key Skills:** `Digital Forensics`, `Disk Forensics`, `Autopsy`, `Evidence Analysis`
*   **[Review the Case File Here](https://github.com/Dorakhris/Forensics-Analysis-The-Stolen-Szechuan-Sauce)**

### Phishing Email Analysis
I conducted a forensic breakdown of a malicious email, analyzing its headers with tools like MXToolbox to prove it was a spoofing attempt. I successfully identified the attacker's infrastructure and provided clear IoCs for immediate blocking.
*   **Key Skills:** `Phishing Analysis`, `Email Security`, `DFIR`, `Header Analysis`
*   **[View the Analysis Here](https://github.com/Dorakhris/Phishing-Email-Analysis)**

### Splunk-Based Threat Analysis of OpenSSH Logs
I executed a threat hunt in OpenSSH logs using advanced **SPL in Splunk**. My analysis uncovered a live brute-force attack and led to the creation of real-time monitoring dashboards and automated alerts.
*   **Key Skills:** `Splunk`, `SPL`, `Log Analysis`, `Threat Hunting`, `Incident Detection`
*   **[View the Project and SPL Queries Here](https://github.com/Dorakhris/Splunk-Log-Analysis)**

### Threat Intelligence Analysis of DarkSide Ransomware
I created a detailed threat intelligence profile of the **DarkSide ransomware group**. My report included mapping their TTPs to the **MITRE ATT&CK framework** and aligning defensive controls with NIST 800-53.
*   **Key Skills:** `Threat Intelligence`, `MITRE ATT&CK`, `NIST 800-53`, `OSINT`
*   **[See the Threat Intelligence Profile Here](https://github.com/Dorakhris/Threat-Intelligence-Analysis-of-Ransomeware)**

### Static & Dynamic Malware Analysis of a .NET Trojan
I performed a full analysis of an obfuscated .NET trojan. The investigation involved reverse-engineering its persistence mechanism and communication protocol, culminating in the creation of a custom **YARA rule** for proactive detection.
*   **Key Skills:** `Malware Analysis`, `Reverse Engineering`, `Static & Dynamic Analysis`, `YARA`
*   **[Read the Full Analysis Report Here](https://github.com/Dorakhris/Malware-Analysis)**


### Vulnerability Management & Automated Remediation with Ansible
This project demonstrates an end-to-end vulnerability management program. I identified critical CVEs on a web server using **Nessus**, then developed an **Ansible playbook for automated remediation**, ensuring a rapid and consistent fix. The project also included a strategic risk analysis of an exposed database, showcasing my ability to translate technical findings into quantifiable business risks.
*   **Key Skills:** `Vulnerability Management`, `Ansible`, `Automation`, `Nessus`, `Risk Assessment`
*   **[See the Analysis and Playbook Here](https://github.com/Dorakhris/Vulnerability-Assessment-lab/blob/main/README.md)**

### GRC Audit of a Retail Business (Botium Toys)
Acting as an internal auditor, I conducted a formal security audit using the **NIST Cybersecurity Framework (CSF)**. I assessed the company’s security posture against key regulations like **PCI DSS** and **GDPR**, identifying critical deficiencies. The final deliverable was a prioritized, actionable roadmap for remediation, demonstrating my ability to bridge technical gaps with strategic business objectives.
*   **Key Skills:** `GRC`, `Security Auditing`, `NIST CSF`, `PCI DSS`, `GDPR`
*   **[Review the Audit Report Here](https://github.com/Dorakhris/Security-audit/blob/main/README.md)**



## Credentials

*   ISO 27001 Lead Auditor (Mastermind)
*   Cisco Junior Cybersecurity Analyst
*   Google Cybersecurity Professional Certificate
*   Arcx Cyber Threat Intelligence Practitioner
*   CompTIA Security+ (in-view)



## Connect With Me

I am always open to discussing new opportunities and connecting with other professionals in the security community.

*   **[LinkedIn Profile](https://www.linkedin.com/in/dorathychristopher/)**
*   **[Medium Articles](https://medium.com/@dorathychristopher/)**
