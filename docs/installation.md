# 📦 Wazuh SIEM Installation Guide

## Overview

This document explains how I installed and deployed my Wazuh SIEM home lab using Kali Purple in a VirtualBox environment.

The purpose of this guide is to document my installation process so that I can recreate the environment in the future and help others understand how my lab was built.

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Virtualization | VirtualBox |
| SIEM Platform | Wazuh |
| Server Operating System | Kali Purple |
| Monitored Endpoints | Windows Server 2025, Windows 11 Enterprise |
| Network | VirtualBox Internal Network |

---

## Installation Workflow

The deployment followed these general steps:

1. Create the Kali Purple virtual machine.
2. Update the operating system.
3. Install the Wazuh platform using the Kali Purple package.
4. Verify that the Wazuh services are running.
5. Access the Wazuh Dashboard from a Windows 11 virtual machine.
6. Install the Wazuh agent on Windows endpoints.
7. Register the agents with the Wazuh server.
8. Verify successful communication between the server and agents.


# Useful Commands

## Check Manager

```bash
sudo systemctl status wazuh-manager
```

---

## Restart Manager

```bash
sudo systemctl restart wazuh-manager
```

---

## Restart Dashboard

```bash
sudo systemctl restart wazuh-dashboard
```

---

## Restart Indexer

```bash
sudo systemctl restart wazuh-indexer
```

---

## Check Services

```bash
sudo systemctl status wazuh-*
```

---

## Find Server IP

```bash
ip addr
```

---

## Check Listening Ports

```bash
sudo ss -tulpn
```
