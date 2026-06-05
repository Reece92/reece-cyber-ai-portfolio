# Secure Home Lab Environment

**Project Overview**: A fully isolated virtual lab for practicing cybersecurity operations, network defence, and safe penetration testing.  

**Defence Relevance**: Demonstrates core skills required for cyber roles in the Australian Defence Force and ASD — network segmentation, hardening, monitoring, and controlled testing environments.

## Architecture
- **Router/Firewall**: pfSense
- **Attacker Machine**: Kali Linux
- **Target Machine**: Windows 11
- **Monitoring**: (Snort/Suricata + logging - to be added)

## Features
- Isolated virtual network (no leakage to host/internet)
- Strict firewall rules
- System hardening documentation
- Simulated attack & detection exercises

[Setup Guide](./docs/setup-guide.md)  
[Hardening Steps](./docs/hardening.md)  
[Attack Demo](./docs/attack-demo.md)

## Technologies Used
- VirtualBox
- pfSense, Kali Linux, Windows 11
- Wireshark, Nmap
