# 🛡️ Security Incident Reports

This folder contains real world and simulated cybersecurity incident reports completed as part of hands-on exercises and portfolio building activities during my cybersecurity learning journey.

Each report uses industry standard practices such as **NIST CSF**, **MITRE ATT&CK**, or **incident handler journaling**, and demonstrates practical skills in **threat detection**, **network analysis**, **malware investigation**, and **incident response**.

---

## 📁 Incident Reports Included

---

### 1. **DNS ICMP Traffic Report**
- **Focus:** Malicious traffic detection
- **Tools Used:** Wireshark, Suricata

---

### 2. **Drive-By Download & Brute Force Attack Report**
- **Focus:** Malware delivery and credential-based attack patterns
- **Frameworks:** MITRE ATT&CK, Log analysis

---

### 3. **Network Hardening Risk Assessment**
- **Focus:** Identifying misconfigurations and poor security posture
- **Techniques:** Baseline hardening, open port evaluation

---

### 4. **SYN Flood Attack Report**
- **Focus:** Denial-of-Service (DoS) behavior via TCP flooding
- **Tools Used:** Packet capture tools, firewall logs

---

### 5. **DDoS Attack – NIST CSF Report**
- **Focus:** Distributed Denial-of-Service incident mapped to the NIST Cybersecurity Framework
- **Structure:** Identify → Protect → Detect → Respond → Recover

---

### 6. **USB Baiting Attack – Rhetorical Hospital**
A scenario-based report on analyzing a suspicious USB device discovered in a healthcare facility.

- Reviewed USB contents and evaluated possible attacker intentions
- Proposed mitigation strategies against USB baiting/social engineering

📄 [USB-Baiting-Attack-Scenario-Rhetorical-Hospital.pdf](./USB-Baiting-Attack-Scenario-Rhetorical-Hospital.pdf)

---

### 7. **Healthcare Ransomware Incident – Incident Journal Entry**
Documented using the **Incident Handler’s Journal** method and the **5 W’s** (Who, What, When, Where, Why).

- Attack started via phishing emails
- Malware encrypted critical healthcare data and disrupted business operations

📄 [Ransomware-Phishing-Incident-Journal-Healthcare-Clinic.pdf](./Ransomware-Phishing-Incident-Journal-Healthcare-Clinic.pdf)

---

### 8. **Phishing Malware Incident – Pyramid of Pain Analysis**
Analyzed a phishing-based malware attack using the **Pyramid of Pain** threat intelligence model.

#### Scenario Summary
A password-protected spreadsheet was sent via phishing email and, when opened, executed a malicious payload. The alert was raised after unauthorized executables were detected.

#### What I Did
- Investigated the file hash using VirusTotal
- Confirmed the file was malicious
- Extracted 3 IoCs: IP address, domain name, and MITRE ATT&CK TTPs

📄 [Phishing-Malware-Pyramid-of-Pain.pdf](./Phishing-Malware-Pyramid-of-Pain.pdf)

---

## 🎯 Purpose

These incident reports demonstrate my ability to:
- Investigate and document cybersecurity incidents
- Apply frameworks like NIST CSF, MITRE ATT&CK, and Pyramid of Pain
- Translate theory into real world application
- Use tools like VirusTotal, Wireshark, and Suricata to detect and analyze threats

They are a key part of my portfolio to show readiness for junior SOC, analyst, or cybersecurity support roles.
