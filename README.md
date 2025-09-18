# LAN Cybersecurity Assessment

**Independent home network security audit demonstrating practical skills in vulnerability identification, network scanning, and mitigation strategies.**

## Objective
Assess the security of a home LAN network, identify potential vulnerabilities, and implement improvements to strengthen overall network security.

## Tools & Technologies
- **Network Scanning & Analysis:** Nmap, ARP, ICMP, TCP/UDP scanning, DNS lookup,
- **Device & IP Verification:** DHCP analysis, AbuseIPDB, MAC OUI lookup & device fingerprinting 
- **Scripting & Automation:** Bash scripting  
- **Network Security Enhancements:** Router administration, VPN setup, OS updates, hashing for integrity verification, VLAN segmentation, MFA, 

## Methodology
- Conducted comprehensive network scans to identify open ports, active devices, and running services  
- Verified device legitimacy and IP reputation using ARP/DHCP tables and AbuseIPDB  
- Tested TCP connections for proper functionality and security  
- Documented vulnerabilities and recommended mitigations  

## Key Improvements & Results
- Router's WAN ports configured to block unnecessary external access while keeping LAN ports safe  
- Router admin interface secured with HTTPS, upgraded router model was ordered; VPN implemented to encrypt external data/traffic
- The network's ONT physical placement and security were verified  
- TCP connections verified for stability and security 
- Enabled and configured device firewall to block all inbound connections except essential services 
- Ran full antivirus deep scan to ensure device was clean  
- Removed unnecessary or risky browser extensions to reduce attack surface
- Implemented device fingerprinting to improve identification of devices on the network, providing detailed profiles for each connected device.
- Devices and router updated to latest firmware/OS versions  
- Guest devices segmented into a separate VLAN to isolate visitors from the main network
- Established incident response procedures:
    - Verified integrity of critical files using SHA-256 hashing for incident preparedness and recovery
    - Implementing regular data backups for recovery in case of compromise

