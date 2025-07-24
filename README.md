# 🕵️‍♂️ Man-in-the-Middle (MitM) Attack Simulation & Network Traffic Analysis

This project demonstrates a **Man-in-the-Middle (MitM)** attack simulation using **Bettercap** on **Kali Linux**, targeting a **Windows 10** machine in a controlled virtual environment. It focuses on analyzing intercepted network traffic and enhancing understanding of network security.

---

## 🎯 Objective

To simulate a MitM attack and analyze intercepted traffic to:

- Understand network vulnerabilities
- Capture unencrypted HTTP credentials
- Improve ethical hacking and cybersecurity skills

---

## ⚙️ Environment Setup

- **Host OS**: Windows 10
- **Virtualization**: VirtualBox / VMware
- **VMs Used**:
  - **Attacker**: Kali Linux
  - **Victim**: Windows 10
- **Network Mode**: Bridged / Host-Only Adapter

---

## 🛠️ Tools & Technologies

- [Bettercap](https://www.bettercap.org/) – ARP spoofing & HTTP proxy
- Wireshark – Packet capture and inspection
- Git, GitHub, Git LFS (for large file support)
- VS Code

---

## 🧪 Steps to Simulate MitM Attack

### 1. **Enable IP Forwarding on Kali**
```bash
echo 1 > /proc/sys/net/ipv4/ip_forward
