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

This lab was built in a VirtualBox environment using **Kali Purple** as the central security monitoring server.

The Wazuh platform was installed directly on the Kali Purple virtual machine. Windows endpoints were configured with the Wazuh agent and connected to the server using the Kali Purple VM's IP address.

Once connected, the agents began sending endpoint data and security events to the Wazuh server, allowing centralized log collection, endpoint monitoring, and security event analysis through the Wazuh Dashboard.

The lab was created to gain practical experience with SIEM deployment and understand how security monitoring is performed in a Security Operations Center (SOC).

> **Note:** A network topology diagram will be added in a future update.


---

# 💻 Virtual Machines

| Virtual Machine | Purpose |
|-----------------|---------|
| Kali Purple | Wazuh Server, Wazuh Dashboard, and Wazuh Indexer |
| Windows Server 2025 | Domain Controller and Wazuh Agent |
| Windows 11 Enterprise | Monitored Endpoint |
| Windows 11 Enterprise | Additional Monitored Endpoint |


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


--  
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
