# SOC Practical: Log Analysis & Security Monitoring

## Overview

This project demonstrates the practical implementation of **Security Operations Center (SOC)** concepts, focusing on **log analysis, security monitoring, and threat detection**.

The objective is to identify **failed login attempts**, detect **potential brute-force attacks**, and analyze **browser activity** for suspicious behavior using industry-standard tools.

---

## Objectives

* Understand SOC fundamentals and workflows
* Perform **log analysis** using Windows Event Viewer
* Detect **failed login attempts (Event ID 4625)**
* Analyze browser history for suspicious activity
* Implement **log collection and monitoring using Elastic Stack**
* Visualize logs using dashboards and graphs

---

## SOC Fundamentals

A **Security Operations Center (SOC)** is responsible for:

* Continuous monitoring of systems
* Detecting cybersecurity threats
* Responding to incidents in real-time

### SOC Roles:

* **Tier 1 Analyst** → Initial monitoring and alert analysis
* **Tier 2 Analyst** → Incident investigation
* **Tier 3 Analyst** → Threat hunting and advanced analysis

---

## Security Monitoring

Security monitoring helps in:

* Detecting anomalies
* Identifying unauthorized access
* Maintaining system security

---

## Log Management

Log management includes:

* Collection of logs
* Normalization of data
* Secure storage
* Analysis for threat detection

---

## Practical Implementation

### Failed Login Detection

* Used **Windows Event Viewer**
* Filtered logs using **Event ID 4625**
* Identified multiple failed login attempts

---

### Detailed Log Analysis

* Target account: **Dell**
* Source IP: **127.0.0.1**
* Indicates local brute-force attempt

---

### Browser History Analysis

* Analyzed Chrome history
* No suspicious activity detected

---

### Log Collection (Elastic Stack)

* **Filebeat** → Log shipping
* **Elasticsearch** → Log storage & indexing

---

### SIEM Dashboard

* Logs visualized using Elastic SIEM

---

### Log Visualization

* Graphs used to analyze log trends

---

### Dashboard Creation

* Created custom dashboards
* Visualized system activity

---

## Tools Used

* Windows Event Viewer
* Google Chrome
* Elastic Stack (Elasticsearch, Kibana)
* Filebeat

---

## Key Learnings

* Practical understanding of SOC operations
* Log-based threat detection
* Importance of continuous monitoring
* Hands-on experience with SIEM tools

---

## Conclusion

This project successfully demonstrates how **log analysis and monitoring** can detect potential threats like brute-force attacks.

Using **Elastic Stack**, logs were efficiently collected, analyzed, and visualized, improving system security awareness and incident detection capabilities.

---

## Author

**Mitali Sinha**
SOC Intern @ CyArt

---
