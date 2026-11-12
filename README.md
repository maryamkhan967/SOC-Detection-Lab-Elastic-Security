# SOC Detection Lab – Elastic Security

A hands-on Security Operations Center (SOC) detection lab built using **Elastic Security SIEM**, demonstrating the simulation, detection, and investigation of 10 security attack scenarios across Linux and Windows environments.

## Project Overview

This project explores how security events are detected and investigated using Elastic Security. It covers simulated adversary activities, SIEM detection alerts, MITRE ATT&CK mapping, alert severity analysis, and SOC analyst response procedures.

## Lab Environment

- **SIEM:** Elastic Security
- **Endpoint Monitoring:** Elastic Agent & Elastic Defend
- **Operating Systems:** Kali Linux & Windows 10
- **Virtualization:** VirtualBox
- **Framework:** MITRE ATT&CK

## Detection Scenarios

| # | Detection Scenario | MITRE ATT&CK | Severity |
|---|---|---|---|
| 01 | Sudo Command Enumeration | T1033 | Low |
| 02 | Potential Successful SSH Brute Force | T1110 | High |
| 03 | Malware Detection Alert | Endpoint Alert | Critical |
| 04 | Internal Linux SSH Brute Force | T1110 | Medium |
| 05 | Threat Intelligence IP Indicator Match | Threat Intelligence | High |
| 06 | Login Via Unusual System User | T1078 | Medium |
| 07 | Windows Event Logs Cleared | T1070.001 | Low |
| 08 | Windows Account / Group Discovery | T1087 / T1069 | Low |
| 09 | Suspicious Command Execution via WMI | T1047 / T1059.003 | High |
| 10 | Nmap Scan Detection | T1046 | Medium |

## What I Practiced

- Simulating common attacker techniques in an isolated lab.
- Monitoring endpoint telemetry through Elastic Agent.
- Investigating and analyzing SIEM alerts.
- Understanding detection rule triggers and alert severity.
- Mapping suspicious activities to MITRE ATT&CK.
- Performing initial SOC triage and identifying suspicious behavior.
- Understanding the importance of event correlation and log forwarding.

## Key SOC Analyst Learnings

- Correlating failed and successful SSH login attempts.
- Investigating suspicious account activity and privilege enumeration.
- Analyzing malware detection alerts and file hashes.
- Identifying Windows event log clearing activity.
- Investigating suspicious WMI-based command execution.
- Evaluating network scanning and threat intelligence matches.
- Prioritizing alerts based on severity, risk score, and investigation context.

## Lab Documentation

The repository includes documentation and screenshots covering all 10 detection scenarios, their simulated activities, generated Elastic Security alerts, and analyst takeaways.

## Disclaimer

All activities were performed in an isolated lab environment using systems owned by me, strictly for educational and defensive cybersecurity purposes.

---

**Focus Areas:** SOC Operations | SIEM | Detection Engineering | Threat Detection | MITRE ATT&CK | Alert Triage | Linux & Windows Security
