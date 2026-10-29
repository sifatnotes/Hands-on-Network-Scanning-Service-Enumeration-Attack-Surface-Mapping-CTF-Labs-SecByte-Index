# Hands-on-Network-Scanning-Service-Enumeration-Attack-Surface-Mapping-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering attack surface mapping, advanced Nmap port scanning, service fingerprinting, technology stack detection, and deep protocol-specific enumeration (SMB, LDAP, SNMP, FTP, SSH, Web).
# Network Scanning, Service Enumeration & Attack Surface Mapping CTF Labs

Welcome to the **Network Scanning, Service Enumeration & Attack Surface Mapping CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on the foundational reconnaissance phase of security assessments—including **Attack Surface & Perimeter Mapping**, **Advanced Network Scanning (Nmap, Port Discovery)**, **Service Fingerprinting & Tech Detection**, and **Deep Protocol Enumeration (SMB, LDAP, SNMP, FTP, SSH, Web)**.

---

## Lab Collection Index

### 1. Attack Surface Mapping & Network Scanning
* **Attack Surface Mapping Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/attack-surface-mapping-essentials](https://learn.secbyte.org/ctf/attack-surface-mapping-essentials)  
  *Focus:* Discovering external assets, mapping IP spaces, identifying rogue infrastructure, and establishing enterprise perimeter boundaries.

* **Network Scanning Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/network-scanning-essentials](https://learn.secbyte.org/ctf/network-scanning-essentials)  
  *Focus:* Master host discovery techniques (ICMP echo, TCP SYN/ACK pings, UDP discovery), ARP sweeping across local subnets, and managing scan timing templates.

* **Advanced Nmap Techniques**  
  *Lab Link:* [https://learn.secbyte.org/ctf/advanced-nmap-techniques](https://learn.secbyte.org/ctf/advanced-nmap-techniques)  
  *Focus:* Leveraging Nmap Scripting Engine (NSE), firewall/IDS evasion scanning (fragmentation, decoys, source port spoofing), and raw packet manipulation (`-sS`, `-sU`, `-sN`, `-sF`).

<Image src="image_agent_tag_8254024288387224318" alt="Diagram illustrating Nmap SYN port scanning and packet response mechanics" caption="Nmap TCP SYN Port Scanning & Response Mechanics" />

---

### 2. Service Fingerprinting & Technology Identification
* **Service Enumeration Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/service-enumeration-essentials](https://learn.secbyte.org/ctf/service-enumeration-essentials)  
  *Focus:* Identifying listening service versions (`-sV`), probing non-standard port bindings, and analyzing basic banner responses.

* **Banner Blind Service Fingerprinting Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/banner-blind-service-fingerprinting-lab](https://learn.secbyte.org/ctf/banner-blind-service-fingerprinting-lab)  
  *Focus:* Identifying obfuscated or stripped service banners using behavioral probing, timing quirks, and low-level protocol handshake characteristics.

* **Technology Detection Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/technology-detection-lab](https://learn.secbyte.org/ctf/technology-detection-lab)  
  *Focus:* Fingerprinting web server technology stacks (Wappalyzer, WhatWeb, HTTP headers), backend frameworks, CMS versions, and JavaScript libraries.

### 3. Protocol-Specific Deep Enumeration
* **SMB Enumeration Lab: Shares, Users and Misconfigurations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/smb-enumeration-lab-shares-users-and-misconfigurations](https://learn.secbyte.org/ctf/smb-enumeration-lab-shares-users-and-misconfigurations)  
  *Focus:* Enumerating open SMB shares (`enum4linux`, `smbclient`, `crackmapexec`), null session access, user RID cycling, and analyzing share ACL permissions.

<Image src="image_agent_tag_8254024288387224685" alt="Terminal showing Nmap NSE script output for Windows SMB share enumeration" caption="Nmap NSE Windows SMB Share & User Enumeration" />

---

* **LDAP Enumeration Lab: Directory Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ldap-enumeration-lab-directory-drift](https://learn.secbyte.org/ctf/ldap-enumeration-lab-directory-drift)  
  *Focus:* Querying LDAP directory services (`ldapsearch`), extracting domain objects, user attributes, organizational units (OUs), and unauthenticated directory binds.

* **SNMP Enumeration: Hidden Network Map**  
  *Lab Link:* [https://learn.secbyte.org/ctf/snmp-enumeration-hidden-network-map](https://learn.secbyte.org/ctf/snmp-enumeration-hidden-network-map)  
  *Focus:* Brute-forcing community strings (`snmpwalk`, `onesixtyone`), querying MIB trees, and extracting routing tables, system users, and network interfaces.

* **FTP Enumeration Foundations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ftp-enumeration-foundations](https://learn.secbyte.org/ctf/ftp-enumeration-foundations)  
  *Focus:* Testing anonymous FTP access, bouncing scans, inspecting directory trees, downloading hidden configuration files, and assessing bounce vulnerabilities.

* **SSH Enumeration: From Banner Grabs to Key Discovery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ssh-enumeration-from-banner-grabs-to-key-discovery](https://learn.secbyte.org/ctf/ssh-enumeration-from-banner-grabs-to-key-discovery)  
  *Focus:* Extracting SSH server algorithms (`ssh-audit`), identifying weak ciphers/KEX methods, probing user enumeration vulnerabilities, and discovering public host keys.

* **Web Enumeration: From Surface to Hidden Attack Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/web-enumeration-from-surface-to-hidden-attack-paths](https://learn.secbyte.org/ctf/web-enumeration-from-surface-to-hidden-attack-paths)  
  *Focus:* Mapping web application entry points, dissecting `robots.txt` and sitemaps, discovering API endpoints, and identifying unlinked administrative panels.

---

## Learning Path

### Path A: Network Reconnaissance & Port Scanning Specialist
1. **Perimeter Mapping:** Start with [Attack Surface Mapping Essentials](https://learn.secbyte.org/ctf/attack-surface-mapping-essentials) and [Network Scanning Essentials](https://learn.secbyte.org/ctf/network-scanning-essentials).
2. **Advanced Scanning:** Master Nmap features in [Advanced Nmap Techniques](https://learn.secbyte.org/ctf/advanced-nmap-techniques).
3. **Fingerprinting:** Identify targets via [Service Enumeration Essentials](https://learn.secbyte.org/ctf/service-enumeration-essentials), [Banner Blind Service Fingerprinting](https://learn.secbyte.org/ctf/banner-blind-service-fingerprinting-lab), and [Technology Detection Lab](https://learn.secbyte.org/ctf/technology-detection-lab).

### Path B: Deep Protocol & Service Enumeration Specialist
1. **Network Services:** Practice service discovery in [SMB Enumeration Lab](https://learn.secbyte.org/ctf/smb-enumeration-lab-shares-users-and-misconfigurations), [LDAP Enumeration Lab](https://learn.secbyte.org/ctf/ldap-enumeration-lab-directory-drift), and [SNMP Enumeration](https://learn.secbyte.org/ctf/snmp-enumeration-hidden-network-map).
2. **Access Protocols & Web:** Enumerate infrastructure protocols in [FTP Enumeration Foundations](https://learn.secbyte.org/ctf/ftp-enumeration-foundations), [SSH Enumeration](https://learn.secbyte.org/ctf/ssh-enumeration-from-banner-grabs-to-key-discovery), and [Web Enumeration](https://learn.secbyte.org/ctf/web-enumeration-from-surface-to-hidden-attack-paths).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise environment hosted on Learn SecByte.
3. Review scenario directives, target IP ranges, or domain parameters.
4. Execute Nmap network scans, fingerprint obfuscated banners, run SNMP walk queries, or dump SMB shares to capture flags.

---

## Target Audience

* **Penetration Testers & Red Team Operators:** Execute stealthy port scans, map enterprise attack surfaces, and perform deep service enumeration.
* **Security Auditors & Vulnerability Assessor Teams:** Identify open network ports, exposed SMB shares, unauthenticated LDAP binds, and legacy SNMP services.
* **SOC Analysts & Blue Teamers:** Understand network scan signatures, detect port scanning probes, and audit perimeter exposures.
* **Cybersecurity Students:** Master Nmap command options, protocol enumeration tools (`enum4linux`, `snmpwalk`), and reconnaissance methodologies.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning or probing against external systems is strictly prohibited.
