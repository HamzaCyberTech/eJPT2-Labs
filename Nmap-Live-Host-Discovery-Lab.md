# Nmap Live Host Discovery - TryHackMe Lab

## Overview
Completed the Nmap Live Host Discovery lab to practice identifying active hosts within a network. The objective was to use Nmap’s host discovery techniques to determine which systems are online and potentially accessible for further enumeration.

## Tools & Techniques
- Nmap host discovery (`-sn`, `-Pn`, `-PS`, `-PA`)
- ICMP echo requests (ping sweeps)
- TCP SYN and ACK probes
- ARP requests for local network discovery
- Service detection for responsive hosts

## Steps
1. Used `nmap -sn` to perform a ping sweep across the target range.
2. Applied `-PS` and `-PA` flags to probe specific TCP ports for host responsiveness.
3. Leveraged `-Pn` to bypass ICMP restrictions and assume hosts are online.
4. Conducted ARP scans to identify live hosts on the local subnet.
5. Documented responsive hosts for follow‑up service enumeration.

## Key Findings
- Successfully identified multiple live hosts within the target network.
- Discovered hosts that blocked ICMP but responded to TCP probes.
- ARP scanning proved highly effective for local network discovery.
- Built a baseline map of active systems for subsequent reconnaissance.

## Lessons Learned
- Host discovery is a critical first step in penetration testing.
- Different probes (ICMP, TCP, ARP) yield varying results depending on firewall rules.
- Using multiple discovery methods increases accuracy and reduces false negatives.
- Proper documentation ensures smooth transition into service enumeration and vulnerability analysis.

![Nmap Live Host Discovery Badge](https://github.com/HamzaCyberTech/eJPT2-Labs/blob/main/Nmap-Live-Host-Discovery-Badge.png)
