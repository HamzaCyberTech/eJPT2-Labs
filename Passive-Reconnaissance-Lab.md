# Passive Reconnaissance - TryHackMe Lab

## Overview
Conducted passive reconnaissance to gather intelligence on a target organization without direct interaction, simulating the initial phase of a penetration test.

## Tools & Techniques
- WHOIS lookups for domain ownership
- DNS record enumeration (MX, NS, TXT)
- Search engine queries (Google dorks)
- Public data sources (Shodan, Censys)
- OSINT from social media and public documents

## Steps
1. Collected registrar and hosting details via WHOIS.
2. Identified DNS records to map infrastructure.
3. Applied Google dorks to locate exposed files.
4. Queried Shodan for publicly accessible services.
5. Researched employee data through LinkedIn and other OSINT platforms.

## Key Findings
- Hosting provider and registrar information revealed.
- Subdomains discovered through passive DNS records.
- Metadata in public documents exposed usernames.
- Potential attack surface mapped without active probing.

## Lessons Learned
- Passive reconnaissance is stealthy and leaves no footprint.
- Combining multiple OSINT sources strengthens intelligence gathering.
- Documentation of findings is critical for transitioning to active testing.
