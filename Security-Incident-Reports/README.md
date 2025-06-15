# Security Incident Reports

This folder contains real-world and simulated cybersecurity incident reports created as part of hands-on exercises in cybersecurity learning. Each report follows industry-standard frameworks such as NIST CSF or general best practices, focusing on detection, analysis, response, and mitigation.

## 📁 Incident Reports Included

1. **DNS-ICMP-Traffic-Report**  
   - Focus: Malicious traffic detection  
   - Tools: Wireshark, Suricata

2. **Drive-By-Download & Brute Force Attack Report**  
   - Focus: Malware delivery + weak credential exploitation  
   - Framework: MITRE ATT&CK, Log Review

3. **Network Hardening Risk Assessment**  
   - Focus: Misconfiguration & security posture analysis  
   - Techniques: Baseline hardening, port review

4. **SYN Flood Attack Report**  
   - Focus: Denial-of-Service traffic behavior  
   - Tools: Packet analysis, Firewall log inspection

5. **DDoS Attack – NIST CSF Report**  
   - Focus: Analyze DDoS using NIST Cybersecurity Framework  
   - Structure: Identify, Protect, Detect, Respond, Recover
  
6. **USB Baiting Attack – Rhetorical Hospital**

In this scenario-based assignment from the Google Cybersecurity Certificate, I played the role of a security team member at Rhetorical Hospital. A suspicious USB drive was found in the parking lot with HR-related files. The task was to:

- Review the contents of the USB
- Analyze how an attacker could use this data
- Propose mitigation strategies to reduce organizational risk

📄 [USB-Baiting-Attack-Scenario-Rhetorical-Hospital.pdf](./USB-Baiting-Attack-Scenario-Rhetorical-Hospital.pdf)

7. **Healthcare Ransomware Incident – Incident Journal Entry**

This entry documents a ransomware attack that occurred at a small U.S. healthcare clinic. The incident began with phishing emails that led to malware execution and file encryption. This was recorded in an Incident Handler’s Journal format using the 5 W’s method.

📄 [Ransomware-Phishing-Incident-Journal-Healthcare-Clinic.pdf](./Ransomware-Phishing-Incident-Journal-Healthcare-Clinic.pdf)


8. **Phishing Malware Incident – Pyramid of Pain Analysis**

This document analyzes a phishing based malware attack using the **Pyramid of Pain framework**, based on a realistic cybersecurity scenario from the **Google Cybersecurity Professional Certificate**.

#### Scenario Summary
As a Level 1 SOC analyst at a financial services company, I received an alert about a suspicious file downloaded by an employee. The file was a **password-protected spreadsheet** received via email, and opening it triggered a **malicious payload**. Multiple unauthorized executables were created, and an IDS raised an alert.

#### What I Did
I used **VirusTotal** to investigate the file hash and extract:
- A verdict on whether the file is malicious
- 3 **indicators of compromise (IoCs)** including a malicious IP, domain, and TTPs

#### File:
[Phishing-Malware-Pyramid-of-Pain.pdf](./Phishing-Malware-Pyramid-of-Pain.pdf)


---

## Purpose

These reports demonstrate how to investigate security events, assess risk, and apply frameworks in real world scenarios, bridging theory with practice.

