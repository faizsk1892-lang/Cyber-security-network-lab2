# Networkwalks – Week 2: Footprinting & Network Scanning

**Author:** Faizan Shaikh  
**Program / Batch:** B082 – Networkwalks  
**Date:** 11 November 2026

## Project Overview

This repository contains my Week 2 cybersecurity practical activities completed as part of the Networkwalks program. The practical covers reconnaissance, footprinting, and network scanning using Kali Linux tools.

## Phases Covered

| Phase | Description |
|---|---|
| Phase 1 | Reconnaissance & Footprinting – Kali Linux Tools, GHDB, Maltego, theHarvester |
| Phase 2 | Scanning & Network Discovery – Zenmap |

## Tools Used

### 1. Kali Linux Tools
- WHOIS
- WhatWeb
- nslookup
- curl
- Wafw00f
- DNSRecon

### 2. Maltego
Used for visual link analysis to identify and understand relationships between different entities.

### 3. theHarvester
Used to collect publicly available information such as email addresses, hostnames, and subdomains.

### 4. Zenmap – Network Scanning

**Authorized Target / Subnet:** `10.34.170.0/24`

**Scan Profile:** Quick Scan

**Command Used:**
```bash
nmap -T4 -F 10.34.170.0/24
```

**Live Hosts Found:** 2

| IP Address | Open Ports / Services |
|---|---|
| 10.34.170.40 | 21 FTP, 80 HTTP, 135 MSRPC, 139 NetBIOS-SSN, 445 Microsoft-DS, 5432 PostgreSQL, 8000 HTTP-ALT |
| 10.34.170.215 | 53 DNS |

**Scan Summary:**
- Total IP addresses scanned: 256
- Live hosts: 2
- Scan duration: 9.84 seconds
- Nmap version: 7.80

## Screenshots

Add your practical screenshots in this section.

### Kali Linux Setup
![Kali Linux Setup](screenshots/Kali_Installation.png)

### Footprinting with Kali Tools
![Footprinting](screenshots/Footprinting.png)

### Maltego
![Maltego Graph](screenshots/Maltego.png)

### theHarvester
![theHarvester](screenshots/theHarvester.png)

### Zenmap Network Scan
![Zenmap Scan](screenshots/Zenmap_Quick_Scan.png)

## Learning Outcomes

- Practised reconnaissance and footprinting using Kali Linux.
- Learned to collect publicly available information.
- Performed visual link analysis using Maltego.
- Used theHarvester for information gathering.
- Performed network scanning using Zenmap.
- Identified live hosts, open ports, and services.

## Disclaimer

All activities were performed for educational purposes in an authorized lab environment. Scanning and testing should only be conducted on systems and networks where permission has been granted.

## Author

**Faizan Shaikh**  
Cybersecurity Professional – B084

**LinkedIn:** https://www.linkedin.com/in/waqaskarim/
