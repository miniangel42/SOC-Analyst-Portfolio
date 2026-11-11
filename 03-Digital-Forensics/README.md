# Digital Forensics — Linux Persistence Investigation

## Project Overview

Conducted a forensic investigation of a compromised Ubuntu 24.04 workstation in a controlled cybersecurity lab environment.

The objective was to identify attacker persistence mechanisms, examine evidence of unauthorized activity, and document detection and remediation procedures.

## Environment and Tools

- Ubuntu 24.04 LTS
- Linux CLI
- Bash
- Cron and system configuration files
- MITRE ATT&CK Framework
- CWE and CVSS v3.1

## Key Findings

Identified five attacker persistence mechanisms:

### 1. MOTD Backdoor
- Discovered a malicious script in `/etc/update-motd.d/`.
- Identified a reverse-shell command triggered during user login.

### 2. Cron Job Persistence
- Discovered a suspicious scheduled task executing every 10 minutes.
- Investigated a reference to a deleted script.

### 3. Bash Configuration Backdoor
- Identified a reverse shell embedded in `.bashrc`.
- Analyzed its execution during interactive Bash sessions.

### 4. Command Hijacking
- Found a malicious `curl` alias redirecting execution to an attacker-controlled script.
- Investigated associated reverse-shell activity.

### 5. USB-Based Persistence
- Identified a malicious udev rule triggered by USB device insertion.
- Examined the associated script and its outbound connection.

## Investigation Methodology

1. Examined Linux configuration files and scheduled tasks.
2. Identified suspicious scripts and unauthorized modifications.
3. Investigated persistence triggers and reverse-shell commands.
4. Collected indicators of compromise (IOCs).
5. Mapped findings to MITRE ATT&CK techniques.
6. Assessed vulnerabilities using CWE and CVSS.
7. Documented remediation procedures and an incident timeline.

## Skills Demonstrated

- Linux Digital Forensics
- Persistence Mechanism Detection
- Incident Response
- IOC Identification
- Bash Script Analysis
- MITRE ATT&CK Mapping
- Security Documentation

## Full Report

[View Full Digital Forensics Report (PDF)](./FZTD%202.0%20Digital%20Forensic%20-%20Incident%20Response%20Report.pdf)

## Disclaimer

This investigation was conducted in an authorized cybersecurity training environment for educational purposes.
