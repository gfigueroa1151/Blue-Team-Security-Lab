# Blue-Team-Security-Lab
A home Active Directory security lab demonstrating five end-to-end attacks and detections, with full incident reports mapped to MITRE ATT&amp;CK.

This repository documents a home cybersecurity lab built to develop and validate detection logic against real-world Active Directory attacks.
The environment consists of a Windows Server 2022 domain controller, a Kali Linux attacker, Sysmon for endpoint telemetry, and Splunk as the SIEM, all running on a self-built virtualized infrastructure. 
Five distinct attacks were executed and detected end-to-end: password spraying, Kerberoasting, LLMNR/NBT-NS poisoning resulting in Domain Administrator compromise, BloodHound enumeration, and malicious PowerShell execution.
Each attack is documented in a professional incident report covering the attack timeline, detection analysis, indicators of compromise, Splunk SPL queries, MITRE ATT&CK mapping, and prioritized remediation recommendations.
