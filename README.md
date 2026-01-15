# FUTURE_CS_02 – Cyber Security Task 2

## Security Alert Monitoring and Incident Response

This repository contains the **Incident Response Report** for **Cyber Security Task 2: Security Alert Monitoring and Incident Response**, completed as part of the **Future Interns Cyber Security Internship Program**.

The objective of this task was to simulate real-world Security Operations Center (SOC) activities by monitoring security alerts, analyzing log data, identifying potential threats, and documenting incident response actions using **SIEM (Security Information and Event Management)** concepts.

---

## 📌 Task Overview

The task focuses on the following key areas:

* Monitoring simulated security alerts using a SIEM platform
* Analyzing system and authentication logs to detect suspicious behavior
* Identifying and classifying potential security incidents
* Documenting incident response actions based on observed threats

The analysis was performed using **simulated SSH authentication logs** to represent real-world security events. No live or real-time attacks were conducted.

---

## 🛠️ Tools and Methodology

### Tools Used

* **Splunk Enterprise (Free Trial)** – Used as the SIEM platform for log ingestion, search, and analysis
* **Simulated SSH Authentication Logs** – Used as input data for detecting suspicious login activity

### Methodology

1. Installed and configured Splunk Enterprise locally
2. Uploaded simulated SSH authentication log files into Splunk
3. Performed log searches and filtering to identify abnormal patterns
4. Detected multiple failed SSH login attempts from the same IP address
5. Classified the activity as a **potential brute-force attack**
6. Documented findings and recommended incident response actions

---

## 🚨 Incident Detection and Analysis

During log analysis, repeated failed SSH login attempts were observed from a single IP address within a short time period. This behavior is commonly associated with:

* Brute force attacks
* Unauthorized access attempts
* Credential-guessing attacks

Based on the observed patterns, the incident was classified as a **Medium to High Severity Security Incident**, requiring further investigation and mitigation.

---

## 🛡️ Incident Response Actions

The following response actions were documented in the report:

* Identification of the suspicious source IP address
* Recommendation to block or blacklist the IP using firewall rules
* Enforcing strong password and authentication policies
* Suggesting implementation of multi-factor authentication (MFA)
* Continuous monitoring and alerting for repeated failed login attempts

---

## 📂 Repository Contents

* **Incident Response Report (PDF/DOCX)**

  * Detailed documentation of the incident analysis and response process
* **ssh_logs.txt**

  * Sample simulated SSH authentication log file used for analysis
* **Screenshots/**

  * Visual evidence of Splunk installation, log ingestion, and analysis

---

## 📸 Screenshot Descriptions

The screenshots included in this repository demonstrate the complete monitoring and analysis workflow:

* **splunk_dashboard.png**
  Displays the Splunk Enterprise dashboard after successful installation and login.

* **log_upload.png**
  Shows the successful upload and ingestion of simulated SSH authentication logs into Splunk.

* **failed_login_search.png**
  Highlights Splunk search results showing multiple failed SSH login attempts from the same IP address, indicating a potential brute force attack.

---

## 📘 Learning Outcomes

Through this task, the following skills were developed:

* Understanding of SIEM concepts and security alert monitoring
* Hands-on experience with Splunk Enterprise
* Log analysis and threat detection techniques
* Incident classification and response documentation
* Practical exposure to SOC-style workflows

---

## ⚠️ Disclaimer

This project is strictly for **educational and training purposes**. All logs and incidents analyzed are simulated, and no real systems or networks were attacked or compromised.
