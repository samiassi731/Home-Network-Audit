# LAN Cybersecurity Audit

**Independent home network security audit demonstrating hands-on skills in vulnerability identification, network scanning, and mitigation strategies. Focused on improving overall network security, device integrity, and operational resilience.**

## Objective
Assess the security of a home LAN network, identify vulnerabilities, and implement improvements to strengthen network defenses and reduce attack surface.  

## Tools & Technologies
- **Network Scanning & Analysis:** Nmap, ARP, ICMP/TCP/UDP scanning, DNS lookup  
- **Device & IP Verification:** DHCP analysis, ARP cache table, AbuseIPDB, MAC OUI lookup (Wireshark), 
- **Scripting & Automation:** Bash scripting  
- **Network Security Enhancements:** Router administration, VPN setup, VLAN segmentation, OS/firmware updates, MFA for confidential files, hashing for integrity verification  

## Methodology
- Conducted comprehensive network scans to identify open ports, active devices, and running services  
- Verified device legitimacy and IP reputation using Wireshark with MAC OUI lookup, DHCP/ARP tables, and AbuseIPDB  
- Tested TCP connections for stability and security, including DNS verification of all connections  
- Documented vulnerabilities and implemented mitigations  

## Key Improvements & Results

### Network & Router Hardening
- Secured WAN ports and disabled login to router interface from the WAN  
- Enabled and configured device firewall to block all inbound connections except essential services
- Disabled WPS and unsecured HTTP access; implemented HTTPS for router admin interface and ordered router upgrade  
- Segmented guest devices into a separate VLAN to isolate visitors from the main network  
- Implemented VPN to encrypt all external traffic  

### Device Verification & Integrity
- Applied latest OS/firmware updates and ran full antivirus scans to ensure device hygiene  
- Reviewed and removed untrusted or risky browser extensions to reduce attack surface  
- Enabled MFA for confidential files to enhance data protection  
- **Implemented Fing fingerprinting** to improve device identification and create detailed profiles for connected devices  
- Established incident response procedures with SHA-256 file integrity checks and regular backups  



