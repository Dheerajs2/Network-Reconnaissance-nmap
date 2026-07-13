# Network Reconnaissance using Nmap

## Overview

This project demonstrates network reconnaissance performed against a Metasploitable 2 virtual machine in an isolated VMware Workstation environment using Nmap.

The objective was to identify live hosts, enumerate open ports, detect running services, identify service versions, and determine the operating system of the target machine.

---

## Lab Environment

- VMware Workstation 17
- Kali Linux
- Metasploitable 2

---

## Tools Used

- Nmap
- Linux Terminal

---

## Objectives

- Verify connectivity
- Perform host discovery
- Enumerate open ports
- Detect service versions
- Identify operating system
- Analyze exposed network services
- Document findings

---

## Commands Used

```bash
ping <Target-IP>

nmap <Target-IP>

nmap -sV <Target-IP>

sudo nmap -O <Target-IP>

sudo nmap -A <Target-IP>
```

---

## Key Findings

- Target host successfully discovered.
- Multiple TCP ports identified.
- Services including FTP, SSH, HTTP, SMB, MySQL, PostgreSQL, and Apache Tomcat detected.
- Operating system fingerprinted as Linux.
- Anonymous FTP login identified.

---

## Learning Outcomes

- Network reconnaissance
- Port scanning
- Service enumeration
- OS fingerprinting
- Attack surface identification
- Nmap reporting

---

## Disclaimer

This project was conducted in a personal lab environment using Metasploitable 2, an intentionally vulnerable virtual machine designed for cybersecurity training.