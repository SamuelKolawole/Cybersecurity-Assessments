# Cybersecurity Incident Report – DDoS Attack (NIST CSF Analysis)

**Scenario**:  
A multimedia company that provides web and graphic design services experienced a Distributed Denial of Service (DDoS) attack. This report analyzes the incident using the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), detailing the event and suggesting improvements under the Identify, Protect, Detect, Respond, and Recover categories.

**Course Context**:  
This report was prepared as part of a cybersecurity assignment to demonstrate practical application of the NIST CSF in analyzing a real world incident.

---

**Incident report analysis**

| Summary | The company’s internal network was disrupted for two hours due to a Distributed Denial of Service (DDoS) attack. The attacker used a flood of ICMP (ping) packets to overwhelm the network, causing all internal network services to become unresponsive. Upon investigation, it was discovered that an unconfigured firewall allowed these malicious packets to enter the network. The incident was resolved by blocking ICMP packets and temporarily shutting down non critical services. Remediation steps were taken to prevent recurrence. |  |  |
| :---- | :---- | ----- | ----- |
| Identify | **Type of attack:** Distributed Denial of Service (DDoS) via ICMP flooding. **Attack vector:** ICMP packets entering through an unconfigured firewall. **Systems affected:** Internal network infrastructure Network services (e.g., internal servers, shared drives, databases) Access to online and hosted services used by internal staff **Vulnerabilities:** Lack of firewall configuration Absence of source IP verification No rate-limiting controls for ICMP traffic |  |  |
| Protect | To better protect internal assets and avoid future attacks: Update firewall configuration to block or rate-limit ICMP packets from unknown or untrusted sources. Implement access control lists (ACLs) to define trusted IPs and deny unverified incoming traffic. Provide employee training on incident reporting and network usage best practices. Apply source IP address verification to help prevent IP spoofing. Review network security policies and regularly audit firewall rules and settings. |  |  |
| Detect | To enhance detection capabilities and reduce response times: **Deploy network monitoring software** that can detect abnormal spikes in ICMP or other traffic types. **Use Intrusion Detection/Prevention Systems (IDS/IPS)** to flag suspicious packet patterns. **Log and analyze network traffic** in real-time to identify patterns consistent with DDoS activity. **Set alerts for anomalies** such as unexpected ICMP packet surges or unusual access times. **Monitor user accounts and devices** to identify unauthorized logins or misconfigured endpoints. |  |  |
| Respond | Response plan to handle future incidents more effectively: **Immediately isolate affected network segments** or devices to contain the attack. **Shut down non-critical services** to preserve system resources during attacks. **Block attack vectors (e.g., ICMP)** using updated firewall rules. **Analyze logs and alerts** to determine the source and nature of the incident. **Conduct a post-incident review** to document lessons learned and update the incident response plan accordingly. **Coordinate with ISPs or third-party vendors** if the attack is beyond internal capacity. |  |  |
| Recover | Steps to recover systems and restore operations: **Restore critical network services first**, such as internal DNS, authentication servers, and shared systems. **Verify system integrity** before bringing non-critical services back online. **Communicate recovery progress** to all stakeholders, including staff and leadership. **Evaluate system performance post-recovery** to ensure no lingering effects remain. **Update documentation** to reflect all recovery actions taken, lessons learned, and improvements made. |  |  |

---

| Reflections/Notes:  The ICMP flood exposed a critical gap in firewall configuration. The attack highlighted the need for automated monitoring and a clearer response workflow. This incident helped justify investments in network security tools such as IDS/IPS and real-time traffic analyzers. Future efforts will focus on better baseline traffic profiling to detect deviations quickly. |
| :---- |

