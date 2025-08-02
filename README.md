# Dorathy Christopher | Cybersecurity Analyst
DFIR • Threat Intelligence • SOC Operations • Auditing

Hello, I'm Dorathy. I am a detail-oriented Cybersecurity Analyst dedicated to protecting digital infrastructures. My passion lies in the full spectrum of defensive security, from proactively hunting for threats in a Security Operations Center to conducting deep-dive digital forensics and malware analysis.

My technical skills are now complemented by formal training as an **ISO 27001 Lead Auditor**. This allows me to not only respond to threats but also to formally assess and audit security controls against industry-leading frameworks, bridging the gap between technical implementation and business risk management. I have hands-on experience with a comprehensive suite of tools, including **Splunk, Nessus, Wireshark, Autopsy, Ansible, FTK Imager and Volatility**.

This portfolio is a collection of my projects, each one a practical demonstration of my ability to solve real-world security challenges.

---

## Core Competencies and Skills

| Defensive Operations (Blue Team) | Threat Analysis & Forensics (DFIR) | Governance, Risk, and Compliance (GRC) |
| :--- | :--- | :--- |
| **SIEM & Log Analysis**: Splunk, ELK | **Malware Analysis**: Static & Dynamic, Sandboxing | **Lead Auditing**: ISO 27001 |
| **Network Security Monitoring**: Wireshark, Zeek | **Digital Forensics**: Autopsy, FTK Imager, Volatility | **Frameworks**: NIST CSF, ISO 27001 |
| **Incident Response**: Triage, Containment, Eradication| **Threat Intelligence**: OSINT, MITRE ATT&CK | **Compliance**: NIST 800-53, PCI DSS, GDPR |
| **Automation & Scripting**: Ansible, Python, Bash | **YARA Rule Creation** | **Risk & Control Assessment** |

---

## Featured Projects

Here are some highlights of my hands-on work, demonstrating my analytical process and technical skills.


### Forensic Investigation of a Spear-Phishing & Data Exfiltration Incident
I was brought in as the lead forensic investigator for a high-stakes incident at M57dotBIZ. A confidential file containing employee PII and salaries was leaked, and the source was traced to the CFO's computer. The situation was tense, as the CFO, Jean Jones, claimed she sent the file at the request of the President, Alison Smith, who adamantly denied it. My task was to use digital evidence to cut through the conflicting stories, establish a definitive chain of events, and find the truth. By performing a deep analysis of email headers, I proved the message was a sophisticated spoof from an external attacker, resolving the internal dispute and identifying the true source of the breach.
*   **Key Skills:** Digital Forensics, Email Forensics, Incident Response, FTK Imager, Social Engineering Analysis
*   **[View the Full Forensic Report Here](https://github.com/Dorakhris/Spear-Phishing-Forensics-Case/blob/main/Spear-Phishing-Forensics-Case/README.md)**

### Vulnerability Management & Automated Remediation with Ansible
This project demonstrates a complete, end-to-end vulnerability management program. I began by identifying critical CVEs on a public-facing Nginx server using **Nessus**. Instead of manual patching, I developed an **Ansible playbook for automated remediation**, ensuring a rapid and consistent fix. The project also included a **strategic risk analysis** of an exposed database server, showcasing my ability to translate technical findings into quantifiable business risks.
*   **Key Skills:** `Vulnerability Management`, `Ansible`, `Automation`, `Nessus`, `Risk Assessment`
*   **[See the Analysis and Playbook Here](https://github.com/Dorakhris/Vulnerability-Assessment-lab/blob/main/README.md)**

### GRC Audit of a Retail Business (Botium Toys)
Acting as an internal auditor, I conducted a formal security audit using the **NIST Cybersecurity Framework (CSF)** as a guide. I assessed the company’s security posture against key regulations like **PCI DSS** and **GDPR**, identifying critical deficiencies in access control and data protection. The final deliverable was a prioritized, actionable roadmap for remediation, demonstrating my ability to bridge technical gaps with strategic business and compliance objectives.
*   **Key Skills:** `GRC`, `Security Auditing`, `NIST CSF`, `PCI DSS`, `GDPR`, `Risk Management`
*   **[Review the Audit Report Here](https://github.com/Dorakhris/Security-audit/blob/main/README.md)**


### Splunk-Based Threat Analysis of OpenSSH Logs
In a simulated SOC environment, I took on the challenge of analyzing live OpenSSH logs to detect an active attack. Using advanced SPL queries, I methodically hunted for anomalies and uncovered a multi-stage attack that included a targeted **brute-force campaign** and **successful user enumeration**. I then built real-time monitoring dashboards and configured automated alerts, turning a reactive investigation into a proactive defense mechanism.
*   **Key Skills:** `Splunk`, `SPL`, `Log Analysis`, `Threat Hunting`, `Incident Detection`
*   **[View the Project and SPL Queries Here](https://github.com/Dorakhris/Splunk-Log-Analysis/blob/main/README.md)**

### Static & Dynamic Malware Analysis of a .NET Trojan
Faced with a suspicious .NET executable protected with "Confuser" obfuscation, I performed a comprehensive analysis to determine its capabilities. My investigation revealed its complete lifecycle: self-replication, establishing persistence through registry modifications, and attempting to communicate with a C2 server. I documented all technical IoCs and authored a custom YARA rule for future detection.
*   **Key Skills:** `Malware Analysis`, `Reverse Engineering`, `Static Analysis`, `Dynamic Analysis`, `YARA`
*   **[Read the Full Analysis Report Here](https://github.com/Dorakhris/Malware-Analysis/blob/main/README.md)**

### Threat Intelligence Analysis of DarkSide Ransomware
To better understand and defend against a prominent threat, I created a detailed intelligence profile on the DarkSide ransomware group. Using VirusTotal and OSINT, I identified the group's common TTPs, mapped these behaviors to the **MITRE ATT&CK framework**, and connected them to relevant **NIST 800-53 controls** to show how specific defenses could mitigate the threat.
*   **Key Skills:** `Threat Intelligence`, `MITRE ATT&CK`, `NIST 800-53`, `OSINT`, `YARA`
*   **[See the Threat Intelligence Profile Here]((https://github.com/Dorakhris/Threat-Intelligence-Analysis-of-Ransomeware/blob/main/README.md))**


### Phishing Email Analysis
I performed a deep forensic analysis of an email impersonating a Microsoft security alert. The investigation involved a meticulous examination of the email headers to trace its path and verify the failure of all **email authentication protocols (SPF, DKIM, DMARC)**. Using tools like MXToolbox and VirusTotal, I proved the email was a **malicious phishing attempt**, identified the attacker's infrastructure, and provided clear IoCs for immediate blocking.
*   **Key Skills:** `Phishing Analysis`, `Email Security`, `DFIR`, `Threat Analysis`, `Header Analysis`
*   **[Read the Full Forensic Report Here](https://github.com/Dorakhris/Phishing-Email-Analysis)**

### Digital Forensics Case: The Stolen Szechuan Sauce
In this scenario, I acted as a forensics investigator tasked with analyzing a compromised disk image to solve a data theft case. Using **Autopsy** and other forensic tools, I uncovered evidence of data exfiltration and unauthorized access by recovering deleted artifacts, analyzing system logs, and piecing together a timeline of the attacker's actions, which I then mapped to the MITRE ATT&CK framework.
*   **Key Skills:** `Digital Forensics`, `Incident Response`, `Autopsy`, `Evidence Analysis`
*   **[Review the Case File Here](https://github.com/Dorakhris/Forensics-Analysis-The-Stolen-Szechuan-Sauce/blob/main/README.md)**


### Incident Handler's Journal: A Multi-Scenario Response
This project documents my experience as a lead incident handler across three distinct, high-pressure scenarios: a **live ransomware attack**, a **data breach and extortion** attempt, and a **proactive vulnerability assessment**. For each case, I used a full suite of tools (Splunk, EDR, Volatility, Nessus) to manage the incident lifecycle, from initial detection and containment to eradication and recovery. The journal showcases my ability to adapt and apply the right skills to different threat contexts while aligning actions with compliance needs like HIPAA and PCI DSS.
*   **Key Skills:** `Incident Response`, `SOC Operations`, `Splunk`, `Ransomware`, `Forensics`
*   **[Explore the Journal Entries Here](https://github.com/Dorakhris/Incident-Journal/blob/main/README.md)**

## Certifications

*   ISO 27001 Lead Auditor (Mastermind)
*   Cisco Junior Cybersecurity Analyst
*   Google Cybersecurity Professional Certificate
*   Arcx Cyber Threat Intelligence Practitioner
*   CompTIA Security+ (in-view)



## Connect With Me

I am always open to discussing new opportunities and connecting with other professionals in the security community.

*   **[LinkedIn Profile](https://www.linkedin.com/in/dorathychristopher/)**
*   **[Medium Articles](https://medium.com/@dorathychristopher/)**
