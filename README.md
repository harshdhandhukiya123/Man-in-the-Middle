# Man-in-the-Middle (MitM) Attack Simulation and Network Traffic Analysis

## 🛡️ Project Overview

This project simulates a **Man-in-the-Middle (MitM) attack** within a secure virtualized environment using **Kali Linux** and **Windows 10**. The goal is to demonstrate potential network vulnerabilities and understand how malicious actors can intercept and manipulate data over an unsecured network.

## ⚙️ Tools & Technologies

- **Operating Systems**: Kali Linux, Windows 10 (in VirtualBox/VMware)
- **Tools Used**:
  - [Bettercap](https://www.bettercap.org/) – for ARP spoofing and packet manipulation
  - Wireshark – for deep packet inspection and network analysis

## 🔧 Setup Instructions

1. **Environment Setup**:
   - Use VirtualBox or VMware to run Kali Linux and Windows 10 on the same host machine or virtual network.
   - Ensure both VMs are on the same network (NAT/Bridge/Host-only adapter).

2. **Install Bettercap on Kali**:
   ```bash
   sudo apt update
   sudo apt install bettercap
