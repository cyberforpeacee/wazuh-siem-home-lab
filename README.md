# 🛡️ Wazuh SIEM Home Lab

## 📌 Overview

This repository documents my hands-on Wazuh SIEM home lab, built to gain practical experience with security monitoring, centralized log management, and threat detection.

Instead of only learning SIEM concepts through theory, I wanted to deploy Wazuh in my own virtual environment, connect multiple endpoints, and understand how security events are collected, analyzed, and investigated in a realistic lab.

The documentation in this repository covers the lab architecture, installation process, configuration steps, screenshots, troubleshooting notes, and the lessons I learned while building the environment.

> **Note:** This project is part of my personal cybersecurity learning journey. It is continuously improved as I expand the lab and gain more hands-on experience.


Note: This project is part of my personal cybersecurity learning journey. It is continuously improved as I expand the lab and gain more hands-on experience.


---

## 📋 Project Information

| Category | Details |
|----------|----------|
| **Project Name** | Wazuh SIEM Home Lab |
| **Project Type** | Cybersecurity Home Lab |
| **Status** | ✅ Completed |
| **Platform** | VirtualBox |
| **Primary Operating System** | Ubuntu Server |
| **Focus Areas** | SIEM, Log Management, Endpoint Monitoring, Threat Detection |


---

## 🎯 Objectives

The primary objectives of this lab were to:

- Build a functional Wazuh SIEM environment from scratch.
- Gain hands-on experience with centralized log collection.
- Monitor Windows and Linux endpoints.
- Understand how security events are generated and analyzed.
- Explore Wazuh dashboards, rules, and alerts.
- Practice investigating security events in a controlled environment.
- Improve my understanding of Security Operations Center (SOC) workflows.



---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Wazuh | Security Information and Event Management (SIEM) |
| Ubuntu Server | Wazuh Server |
| VirtualBox | Virtualization Platform |
| Windows 11 | Monitored Endpoint |
| Sysmon | Endpoint Telemetry |
| Linux | Server Administration |


---

# 🏗️ Lab Architecture

The Wazuh SIEM lab was deployed inside my personal virtualization environment to simulate a small enterprise network. The environment includes Windows and Linux systems connected through VirtualBox networking, allowing me to collect logs, monitor endpoint activity, and investigate security events.

The lab was built as part of my cybersecurity learning journey and is designed to provide hands-on experience with SIEM deployment, endpoint monitoring, and basic SOC operations.

> **Note:** A network topology diagram will be added in a future update.


---

# 💻 Virtual Machines

The following virtual machines were used throughout this lab:

| Machine | Role |
|----------|------|
| Ubuntu Server | Wazuh Server |
| Windows 11 | Monitored Endpoint |
| Ubuntu Desktop *(optional)* | Linux Endpoint / Testing |
| Kali Linux *(optional)* | Attack Simulation |


---

# 🎓 Skills Demonstrated

Through this project, I practiced and strengthened the following skills:

- Deploying and configuring Wazuh SIEM.
- Installing and managing Wazuh agents.
- Centralized log collection.
- Endpoint monitoring.
- Basic threat detection.
- Security event investigation.
- Linux server administration.
- Virtual machine management using VirtualBox.
- Documentation and troubleshooting.


---

# 📂 Repository Structure

```text
wazuh-siem-home-lab/
│
├── README.md
├── screenshots/
├── diagrams/
├── configs/
└── docs/
```
