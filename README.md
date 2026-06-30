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
| **Primary Operating System** | Kali Purple |
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
| Kali Purple | Wazuh Server |
| VirtualBox | Virtualization Platform |
| Windows 11 | Monitored Endpoint |
| Sysmon | Endpoint Telemetry |
| Linux | Server Administration |


---

# 🏗️ Lab Architecture

The Wazuh SIEM lab was deployed inside my personal VirtualBox environment using **Kali Purple** as the Wazuh server. Multiple Windows endpoints were connected to the server through the Wazuh agent, allowing centralized log collection, endpoint monitoring, and security event analysis.

The environment was built as part of my cybersecurity learning journey to better understand how SIEM platforms are deployed and used in Security Operations Center (SOC) environments.

> **Note:** A network topology diagram will be added in a future update.


---

# 💻 Virtual Machines

The following virtual machines were used throughout this lab:

|| Machine | Role |
|----------|------|
| Kali Purple | Wazuh Server |
| Windows Server 2025 | Monitored Endpoint |
| Windows 11 Enterprise | Monitored Endpoint |
| Windows 11 Enterprise | Additional Endpoint |


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

                    VirtualBox Lab

          +------------------------------+
          |       Kali Purple VM         |
          |------------------------------|
          | - Wazuh Server               |
          | - Wazuh Dashboard            |
          | - Wazuh Indexer              |
          +--------------+---------------+
                         |
                         | Wazuh Agent Communication
                         |
        -----------------------------------------
        |                                       |
+----------------------+          +----------------------+
| Windows 11 VM        |          | Windows Server 2025 |
| Wazuh Agent          |          | Wazuh Agent         |
| Endpoint Monitoring  |          | Domain Controller   |
+----------------------+          +----------------------+



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
