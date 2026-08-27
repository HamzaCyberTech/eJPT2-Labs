# Nmap Basic Port Scan - TryHackMe Lab

## Overview
Completed the Nmap Basic Port Scan lab to practice fundamental scanning techniques. The objective was to identify open ports and services on target systems, forming the foundation for deeper enumeration and exploitation.

## Tools & Techniques
- Nmap default scanning (`nmap <target>`)
- TCP connect scans (`-sT`)
- SYN scans (`-sS`)
- Service detection (`-sV`)
- Common port ranges and full port scans (`-p-`)

## Steps
1. Ran a default Nmap scan to identify open ports on the target.
2. Used `-sS` SYN scan for faster and stealthier detection.
3. Applied `-sV` to enumerate service versions running on discovered ports.
4. Conducted full port scans (`-p-`) to ensure no services were missed.
5. Documented results for use in vulnerability analysis and exploitation.

## Key Findings
- Identified multiple open ports exposing services such as HTTP, SSH, and FTP.
- Detected outdated service versions vulnerable to known exploits.
- Built a baseline map of the target’s accessible services.
- Confirmed the importance of scanning all ports, not just common ranges.

## Lessons Learned
- Basic port scanning is the cornerstone of active reconnaissance.
- SYN scans are faster and less detectable compared to full TCP connect scans.
- Service version detection provides critical context for vulnerability research.
- Comprehensive port coverage reduces the risk of overlooking exploitable services.

![Nmap-Basic-Port-Scan](https://github.com/HamzaCyberTech/eJPT2-Labs/blob/main/Nmap-Basic-Port-Scan.png)
