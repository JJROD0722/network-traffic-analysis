# Network Traffic Analysis

Analyzed a training PCAP in Wireshark to identify an affected host and investigate suspicious network activity.

## Findings
- Identified the host, hostname, MAC address, and user account.
- Observed VBScript and obfuscated PowerShell delivery.
- Found repeated HTTP requests suggesting possible C2 polling.
- Distinguished observed evidence from unconfirmed execution and C2 activity.

## Report
[Read the investigation report](Network-Traffic-Investigation.pdf)

## Tools and source
- Wireshark
- Malware-Traffic-Analysis.net: January 22, 2025 training exercise
- https://www.malware-traffic-analysis.net/2025/01/22/index.html
