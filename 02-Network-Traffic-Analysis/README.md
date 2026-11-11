
# Network Traffic Analysis — Incident Response

## Project Overview

Conducted a network forensic investigation of a simulated corporate network compromise at FZTD Industries.

Analyzed PCAP evidence to identify attack techniques, reconstruct the intrusion timeline, and determine the potential impact on compromised systems.

## Tools and Technologies

- Wireshark
- PCAP Analysis
- TCP/IP, HTTP, DNS, ARP
- Network Forensics
- MITRE ATT&CK Framework

## Key Findings

### 1. Network Reconnaissance
- Identified ICMP host discovery and TCP SYN scanning.
- Investigated suspicious communication between network hosts.

### 2. Web Application Attacks
- Detected SQL Injection attempts.
- Identified command injection activity.
- Analyzed suspicious HTTP requests and responses.

### 3. Reverse Shell Activity
- Identified reverse-shell communication over TCP port 4444.
- Examined attacker command execution after initial compromise.
- Reconstructed the sequence of malicious network activity.

### 4. Credential Exposure
- Investigated evidence of compromised application accounts.
- Identified exposure of database configuration files and Linux credentials.
- Examined indicators of potential data exfiltration.

### 5. MITM Investigation
- Checked ARP and DNS traffic for potential Man-in-the-Middle activity.
- Found insufficient evidence to confirm a traditional MITM attack.

## Investigation Methodology

1. Inspected captured network traffic using Wireshark.
2. Applied protocol and IP-based display filters.
3. Investigated suspicious HTTP requests and TCP sessions.
4. Examined reverse-shell communication and attacker commands.
5. Reconstructed the attack timeline.
6. Documented findings and mapped attack techniques to MITRE ATT&CK.

## Skills Demonstrated

- Network Traffic Analysis
- Packet Inspection
- Incident Investigation
- Threat Detection
- Attack Timeline Reconstruction
- Security Reporting

## Full Report

[View Full Incident Response Report (PDF)](./FZTD%202.0%20Network%20Traffic%20Analysis%20-%20Incident%20Response%20Report.pdf)

## Disclaimer

This project was completed in a controlled cybersecurity training environment for educational purposes.
