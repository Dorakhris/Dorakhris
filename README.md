# Dorathy Christopher | Cybersecurity Analyst
DFIR • Threat Intelligence • SOC Operations • Malware Analysis

Hello, I'm Dorathy. I am a detail-oriented Cybersecurity Analyst dedicated to protecting digital infrastructures. My passion lies in the full spectrum of defensive security, from proactively hunting for threats in a Security Operations Center to conducting deep-dive digital forensics and malware analysis.

My work focuses on turning raw, complex data into clear, actionable intelligence. I have hands-on experience with a comprehensive suite of industry-standard tools, including **Splunk, Wireshark, Autopsy, and Volatility**. I am also expanding my expertise into **Governance, Risk, and Compliance (GRC)** to better align technical security controls with strategic business objectives.

This portfolio is a collection of my projects, each one a practical demonstration of my ability to solve real-world security challenges.

---

## Core Competencies and Skills

| Defensive Operations (Blue Team) | Threat Analysis & Forensics (DFIR) | Governance and Frameworks (GRC) |
| :--- | :--- | :--- |
| **SIEM & Log Analysis**: Splunk, ELK | **Malware Analysis**: Static & Dynamic, Sandboxing | **Frameworks**: NIST CSF, ISO 27001 |
| **Network Security Monitoring**: Wireshark, Zeek | **Digital Forensics**: Autopsy, FTK Imager, Volatility | **Compliance**: NIST 800-53 Mapping |
| **Incident Response**: Triage, Containment, Eradication| **Threat Intelligence**: OSINT, MITRE ATT&CK | **Vulnerability Management**: Nessus, OpenVAS |
| **Scripting**: Python, Bash | **YARA Rule Creation** | **Security Auditing & Hardening** |

---

## Featured Projects

Here are some highlights of my hands-on work, demonstrating my analytical process and technical skills.

### Splunk-Based Threat Analysis of OpenSSH Logs
In a simulated SOC environment, I took on the challenge of analyzing live OpenSSH logs to detect an active attack. I began by ingesting and parsing the semi-structured data in Splunk Cloud. Using advanced SPL queries, I methodically hunted for anomalies and uncovered a multi-stage attack that included a targeted **brute-force campaign**, **successful user enumeration**, and other high-risk **Indicators of Compromise (IOCs)**. To make this intelligence actionable, I built real-time monitoring dashboards and configured automated alerts, turning a reactive investigation into a proactive defense mechanism.
*   **Key Skills:** `Splunk`, `SPL`, `Log Analysis`, `Threat Hunting`, `Incident Detection`
*   **[View the Project and SPL Queries Here](https://github.com/Dorakhris/Splunk-Log-Analysis/blob/main/README.md)**

### Static & Dynamic Malware Analysis of a .NET Executable
Faced with a suspicious .NET executable, I performed a comprehensive analysis to determine its capabilities and threat level. The malware was protected with "Confuser" obfuscation, which I worked to bypass. My analysis revealed its complete lifecycle: self-replication into system directories, establishing persistence through registry modifications, and attempting to communicate with a Command and Control (C2) server. I documented all technical IOCs, authored a custom YARA rule for future detection, and provided clear mitigation steps.
*   **Key Skills:** `Malware Analysis`, `Static Analysis`, `Dynamic Analysis`, `Reverse Engineering`, `YARA`
*   **[Read the Full Analysis Report Here](https://github.com/Dorakhris/Malware-Analysis/blob/main/README.md)**

### Threat Intelligence Analysis of DarkSide Ransomware
To better understand and defend against a prominent threat, I created a detailed intelligence profile on the DarkSide ransomware group. Using VirusTotal and open-source intelligence (OSINT), I identified the group's common Tactics, Techniques, and Procedures (TTPs). I then mapped these technical behaviors to the **MITRE ATT&CK framework** to standardize the findings and connected them to relevant **NIST 800-53 controls** to show how specific defenses could mitigate the threat, bridging the gap between technical intelligence and GRC.
*   **Key Skills:** `Threat Intelligence`, `MITRE ATT&CK`, `NIST 800-53`, `OSINT`, `YARA`
*   **[See the Threat Intelligence Profile Here](https://github.com/Dorakhris/Threat-Intelligence-Analysis-of-Ransomeware/blob/main/README.md)**

### Vulnerability Assessment & Automation Lab
Manual vulnerability patching can be slow and inconsistent. To address this, I built a lab to automate the process. I began by performing an authenticated scan on a Linux and Nginx server using **Nessus** to identify weaknesses. Then, I wrote **Ansible playbooks** to automatically apply the necessary patches and system hardening configurations. The project was completed by verifying the fixes with a follow-up scan and configuring automated email reports.
*   **Key Skills:** `Vulnerability Management`, `Nessus`, `Automation`, `Ansible`, `Linux Hardening`
*   **[Explore the Lab and Ansible Playbooks Here](https://github.com/Dorakhris/Vulnerability-Assessment-lab/blob/main)**

### Digital Forensics Case: The Stolen Szechuan Sauce
In this scenario, I acted as a forensics investigator tasked with analyzing a compromised disk image. Using **Autopsy** and other forensic tools, I uncovered evidence of data exfiltration and unauthorized access. My investigation involved recovering deleted artifacts, analyzing system and browser logs, and piecing together a timeline of the attacker's actions, which I then mapped to the MITRE ATT&CK framework to create a clear narrative of the breach.
*   **Key Skills:** `Digital Forensics`, `Incident Response`, `Autopsy`, `Evidence Analysis`
*   **[Review the Case File Here](https://github.com/Dorakhris/Forensics-Analysis-The-Stolen-Szechuan-Sauce/blob/main/README.md)**

---

## Certifications

*   Cisco Junior Cybersecurity Analyst
*   Google Cybersecurity Professional Certificate
*   ArcX Cyber Threat Intelligence Practitioner
*   Comptia Security+ (in-view)

---

## Connect With Me

I am always open to discussing new opportunities and connecting with other professionals in the security community.

*   **[LinkedIn Profile](https://www.linkedin.com/in/dorathychristopher/)**
*   **[Medium Articles](https://medium.com/@dorathychristopher/)**
