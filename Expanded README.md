Active Directory Detection Engineering Lab
A self-built home lab for developing and validating detection logic against real-world Active Directory attacks, modeled on professional SOC workflows.

Overview

This project documents an end-to-end detection engineering effort across an isolated Active Directory environment. The lab consists of a Windows Server 2022 domain controller, a Kali Linux attacker workstation, Sysmon for endpoint telemetry, and Splunk as the SIEM. Each component was deployed, configured, and hardened manually to mirror a small enterprise environment.

Attacks Executed and Detected

Password Spraying (T1110.003) — Credential Access
Kerberoasting (T1558.003) — Credential Access
LLMNR/NBT-NS Poisoning (T1557.001) — Credential Access, full Domain Administrator compromise
BloodHound Enumeration (T1087.002, T1069.002, T1482) — Discovery
Malicious PowerShell Execution (T1059.001) — Execution

Deliverables

Five professional incident reports covering attack timelines, detection analysis, indicators of compromise, Splunk SPL queries, MITRE ATT&CK mapping, and remediation recommendations.
Working Splunk detection rules that successfully fired against live attacks.
Group Policy hardening configurations including Advanced Audit Policy, PowerShell Script Block Logging, and user and computer restrictions.

Skills Demonstrated
Detection engineering, Splunk SPL, Sysmon telemetry analysis, MITRE ATT&CK application, Active Directory administration, Group Policy configuration, professional incident reporting for both technical and non-technical audiences.
