# Elevate_Labs_Internship_Day_3-Task-3

# 🔒 Nessus Vulnerability Assessment - Localhost Scan

This project demonstrates the complete process of performing a **vulnerability scan** on a local machine using **Tenable Nessus Essentials**. It includes installation, configuration, scanning, and result analysis using industry-standard tools and methods.

---

## 📌 Project Overview

Nessus is one of the most popular vulnerability scanners used by security professionals. In this project, we:

- Installed and configured Nessus Essentials
- Scanned the localhost system (127.0.0.1)
- Analyzed and categorized vulnerabilities
- Suggested remediations based on findings

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials) | Vulnerability scanning |
| Web Browser (https://localhost:8834) | Accessing Nessus GUI |
| Windows OS | Target system for scanning |

---

## 🚀 Installation & Setup

1. Downloaded Nessus Essentials from [Tenable Downloads](https://www.tenable.com/downloads/nessus)
2. Installed Nessus on Windows system
3. Opened browser and navigated to: `https://localhost:8834`
4. Registered using name and email to get a **free activation code**
5. Activated Nessus Essentials using the code
6. Waited for initial plugin installation (~15 mins)

---

## 🔍 Scan Process

1. Clicked **"New Scan"**
2. Selected **Basic Network Scan**
3. Named the scan: `Localhost Vulnerability Scan`
4. Set Target to: `127.0.0.1`
5. Launched the scan and waited for completion

---

## 📊 Results & Observations

Scan results categorized by severity:

| Severity | Count | Examples |
|----------|-------|----------|
| High     | 2     | TLS Weak Cipher Support, SMB Signing Not Required |
| Medium   | 3     | Outdated Software Detected |
| Low      | 5     | General Info Leaks |
| Info     | 10+   | OS Details, Service Banners |

Each vulnerability contains:

- Description of the issue
- CVSS score
- Affected ports/services
- Suggested fixes/remediation steps

---

## 📁 Exported Report

The scan report was exported as a **PDF** for documentation and further review.

📄 File: `localhost_vulnerability_report.pdf`  
📂 Location: `/reports/`

---

## 📚 Learning Outcomes

- Understood real-world vulnerability detection process
- Learned about common misconfigurations and security flaws
- Practiced cybersecurity reporting and documentation



## 📄 License

This project is for **educational and academic purposes only**. Nessus Essentials is free for personal use and subject to [Tenable's license](https://www.tenable.com/products/nessus/nessus-essentials).

