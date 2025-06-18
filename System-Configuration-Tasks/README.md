# 🛠️ System Configuration Tasks

This folder contains hands-on system configuration tasks performed in a Linux or secure computing environment. The primary focus is on **file permissions**, **access control**, and **automated user/IP management** using scripting and command-line tools.

---

## 📄 Reports Included

### 1. **Managing Linux File Permissions Report**
A detailed walkthrough of how to manage file permissions on a Linux system using:
- `chmod`, `ls -la`, and permission strings
- Explanations and interpretation of symbolic/absolute modes
- Screenshots, file visibility checks, and permission modifications

📄 [Managing Linux File Permissions Report.pdf](./Managing%20Linux%20File%20Permissions%20Report.pdf)

---

### 2. **IP AllowList Update – Python Automation Script**
A real world access control automation task involving allowlisting and removals based on IP addresses in a healthcare setting.

- Reads a file of approved IPs (`allow_list.txt`)
- Removes any IPs that appear on a separate `remove_list`
- Uses Python to safely update the access list using file operations and list logic

#### Key Python Features Used:
- `open()`, `with` statement, `.read()`, `.write()`
- `.split()`, `.join()`, `.remove()`
- `for` loops and conditionals

📄 [IP-AllowList-Update-Algorithm.pdf](./IP-AllowList-Update-Algorithm.pdf)

---

## 🎯 Objective

This folder demonstrates practical system configuration techniques, including:

- Managing user permissions and file access in Linux
- Automating access control updates using Python
- Strengthening system hardening practices

These are foundational cybersecurity skills relevant to both **system administrators** and **SOC analysts** focused on infrastructure security.

---

## 📁 Cybersecurity Assessments Repository Structure

This folder exists alongside:

- `/security-audits`
- `/security-incident-reports`
- `/tool-comparisons-and-research`
- `/threat-modeling-activities`

Helping to separate **technical system-level exercises** from **audits**, **investigations**, and **analysis tasks**.
