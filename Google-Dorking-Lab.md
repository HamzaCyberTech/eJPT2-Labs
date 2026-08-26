# Google Dorking - TryHackMe Lab

## Overview
Completed the Google Dorking lab to practice advanced search engine techniques for gathering sensitive information. The objective was to identify exposed data, misconfigured resources, and potential attack surfaces using only Google queries.

## Tools & Techniques
- Google search operators (`site:`, `filetype:`, `intitle:`, `inurl:`)
- Query chaining for precise results
- Identification of exposed documents (PDF, DOCX, XLSX)
- Discovery of login portals and admin panels
- Metadata extraction from indexed files

## Steps
1. Applied `site:` operator to restrict searches to specific domains.
2. Used `filetype:` to locate publicly accessible documents.
3. Leveraged `intitle:` and `inurl:` to identify login pages and admin panels.
4. Extracted metadata from discovered files to reveal usernames and system details.
5. Correlated findings to assess potential risks for the target organization.

## Key Findings
- Located sensitive documents indexed by Google.
- Identified login portals exposed to the internet.
- Extracted metadata revealing internal usernames and software versions.
- Demonstrated how misconfigured search visibility can expose critical information.

## Lessons Learned
- Google Dorking is a powerful passive reconnaissance technique requiring no direct interaction.
- Organizations must implement proper indexing controls and robots.txt configurations.
- Regular audits of publicly accessible content are essential to reduce OSINT exposure.

![Google Dorking](https://github.com/HamzaCyberTech/eJPT2-Labs/blob/main/THM%20Google%20Dorking%20Badge.png)
