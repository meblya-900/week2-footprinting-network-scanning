# Week 2 – Footprinting & Network Scanning

## Overview

This repository contains my Week 2 practical work completed during the **Networkwalks Cybersecurity & Ethical Hacking Internship**.

The objective of this week's project was to perform passive reconnaissance and network discovery using industry-standard cybersecurity tools while documenting all findings in a professional penetration testing report.

---

## Modules Completed

### W2-PM1 – Footprinting Using Multiple Kali Linux Tools

The following tools were used:

- WHOIS
- WhatWeb
- Nslookup
- Curl
- Wafw00f
- DNSRecon

These tools were used to gather publicly available information about the target domain, identify technologies, inspect HTTP headers, detect Web Application Firewalls (WAF), and enumerate DNS records.

---

### W2-PM4 – Footprinting Using theHarvester

Performed passive reconnaissance using:

- Baidu
- All Sources

Commands executed:

```bash
theHarvester -d microsoft.com -l 1000 -b baidu

theHarvester -d microsoft.com -l 50 -b all
```

TheHarvester was used to discover:

- Email addresses
- Subdomains
- Hosts
- Publicly available OSINT information

---

### W2-PM5 – Network Scanning with Zenmap

Tasks completed:

- Installed Zenmap
- Identified local subnet
- Performed Ping Scan
- Enumerated live hosts
- Collected IP addresses
- Identified MAC addresses
- Generated network topology

---

## Skills Gained

- Passive Reconnaissance
- Open Source Intelligence (OSINT)
- Domain Enumeration
- DNS Enumeration
- Web Technology Fingerprinting
- HTTP Header Analysis
- WAF Detection
- Network Discovery
- Host Enumeration
- Technical Documentation
- Penetration Testing Reporting

---

## Repository Structure

```
Report/
Screenshots/
Results/
```

---

## Disclaimer

This project was completed strictly for educational purposes as part of the Networkwalks Cybersecurity Internship.

All reconnaissance and scanning activities were performed only against authorized targets or personal lab environments.

No unauthorized testing was performed.
