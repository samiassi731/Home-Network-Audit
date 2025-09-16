# LAN Cybersecurity Assessment

**Independent home network security audit demonstrating practical skills in vulnerability identification, network scanning, and mitigation strategies.**

## Objective
Assess the security of a home LAN network, identify potential vulnerabilities, and implement improvements to strengthen overall network security.

## Tools & Technologies
- **Network Scanning & Analysis:** Nmap, ARP, ICMP, TCP/UDP scanning  
- **Device & IP Verification:** DHCP analysis, AbuseIPDB, MAC OUI lookup  
- **Scripting & Automation:** Bash scripting  
- **Network Security Enhancements:** Router administration, VPN setup, OS updates, hashing for integrity verification, VLAN segmentation

## Methodology
- Conducted comprehensive network scans to identify open ports, active devices, and running services  
- Verified device legitimacy and IP reputation using ARP/DHCP tables and AbuseIPDB  
- Tested TCP connections for proper functionality and security  
- Documented vulnerabilities and recommended mitigations  
- Applied security improvements, including port hardening, VPN deployment, encrypted internal/remote communications, and guest network segmentation via VLAN

## Key Improvements & Results
- Configured to router WAN ports block unnecessary external access while keeping LAN ports safe  
- Router admin interface secured with HTTPS, upgraded router model was ordered; VPN implemented to encrypt internal and remote traffic  
- TCP connections verified for stability and security 
- Enabled and configured device firewall to block all inbound connections except essential services 
- Ran full antivirus deep scan to ensure devices were clean  
- Removed unnecessary or risky browser extensions to reduce attack surface  
- Devices and router updated to latest firmware/OS versions  
- Critical files hashed for future integrity verification  
- Guest devices segmented into a separate VLAN to isolate visitors from the main network
- Established incident response procedures:
    - Resetting router to obtain a new dynamic IP if intrusion occurs  
    - Verified integrity of critical files using SHA-256 hashing for incident preparedness and recovery
    - Implementing regular data backups for recovery in case of compromise

