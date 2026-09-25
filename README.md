# 🛡️ Web & Network Penetration Testing — AOL Project Assessment

![Category](https://img.shields.io/badge/Category-Penetration%20Testing-blue)
![Focus](https://img.shields.io/badge/Focus-Web%20%26%20Network%20Security-red)
![Methodology](https://img.shields.io/badge/Methodology-PTES%20%2F%20OWASP-orange)
![Framework](https://img.shields.io/badge/Scoring-CVSS%20v3.1-brightgreen)

## 📌 Project Overview
This repository contains the security assessment documentation, methodology, and vulnerability findings for the **AOL Project Assessment**. The objective of this project was to conduct a comprehensive security audit covering network reconnaissance, traffic analysis, web application penetration testing, and vulnerability remediation planning.

---

## 👨‍💻 Project Team & Contribution

This security assessment was conducted as a collaborative team effort.

| Contributor | Focus / Area of Responsibility |
| :--- | :--- |
| **Jason Darrell Sebastian** ([@jason-darrell](https://github.com/jason-darrell)) | **Network Reconnaissance, Traffic Inspection (Wireshark), Web Security Assessment & CVSS Risk Scoring** |
| **Team Member 2** ([@username](#)) | Web Application Exploitation & Report Drafting |
| **Team Member 3** ([@username](#)) | Target Subnet Enumeration & Service Mapping |

---

## 🛠️ Tools & Technologies Used

* **Network Reconnaissance & Enumeration:** `Nmap`, `Netcat`
* **Packet & Traffic Analysis:** `Wireshark`
* **Web Application Testing:** `Burp Suite` (Community/Professional)
* **Exploitation & PoC:** `Metasploit Framework`, Custom `Python` Scripts
* **Vulnerability Assessment & Scoring:** `CVSS v3.1 Calculator`

---

## 🔍 Key Assessment Phases & Findings

### 1. Network Reconnaissance & Service Enumeration
* Executed active scanning across target subnet ranges using `Nmap` to map alive hosts, open ports, and running service versions.
* Identified outdated service versions and exposed administrative ports across network segments.

### 2. Network Traffic & Packet Inspection
* Captured and analyzed local network traffic using `Wireshark`.
* Identified unencrypted transmission protocols exposing sensitive credentials and internal data packets over the wire.

### 3. Web Application Security Testing
* Evaluated web application endpoints focusing on:
  * **Authentication & Session Management:** Testing for weak session identifiers and credential brute-force resilience.
  * **Input Validation & Access Control:** Assessing endpoints for potential injection flaws and Broken Object Level Authorization (BOLA).

### 4. Vulnerability Scoring & Remediation Planning
* Calculated standardized **CVSS v3.1** base scores for each identified issue to establish clear threat prioritization.
* Provided actionable defensive recommendations to harden server configurations and secure application code.

---

## 📄 Repository Structure

```text
├── docs/
│   ├── executive_summary.pdf      # High-level assessment summary
│   └── technical_report.pdf       # Detailed technical findings & PoCs
├── scans/
│   ├── nmap_results.txt           # Nmap scan logs (sanitized)
│   └── wireshark_analysis.md      # Traffic analysis breakdown
├── scripts/
│   └── custom_poc.py              # Custom Python verification scripts
└── README.md                      # Project overview and documentation
