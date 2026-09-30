---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0043"
source_url: "https://attack.mitre.org/datacomponents/DC0043"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0043: Firewall Disable

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0043  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The deactivation, misconfiguration, or complete stoppage of firewall services, either on a host or in a cloud control plane. Such activity may involve turning off firewalls, modifying rules to disable protection, or deleting firewall-related configurations and activity logs. Examples: - Disabling Host-Based Firewalls: Stopping the Windows Defender Firewall service or using `iptables -F` to flush all rules on a Linux system. - Cloud Firewall Modification or Deactivation: Modifying or deleting security group rules in AWS or disabling a network firewall in Azure. - Activity Log Deletion: Writing or deleting entries in Azure Firewall Activity Logs to hide unauthorized firewall changes. - Temporary Disable for Malicious Operations: Temporarily disabling a firewall to allow malicious files or traffic, then re-enabling it to avoid detection. - Using Command-Line Tools to Stop Firewalls: Running commands like `Set-NetFirewallProfile -Enabled False on Windows or systemctl stop ufw` on Linux. This data component can be collected through the following measures: Cloud Control Plane - Azure Activity Logs: - Enable logging of administrative actions, such as stopping or modifying Azure Firewall configurations. - Use Azure Monitor to track specific firewall-related actions, including disabling or rule deletion. - AWS CloudTrail Logs: - Monitor `RevokeSecurityGroupIngress` or `RevokeSecurityGroupEgress` events to detect rule changes in AWS Security Groups. - Google Cloud Platform Logs: - Collect logs from the Firewall Rules resource in Google Cloud Operations Suite to detect rule deletions or modifications. Host-Level Firewalls - Windows Firewall Event Logs: - Enable logging of firewall state changes: - Security Event ID 2004: Firewall service stopped. - Security Event ID 2005: Firewall service started. - Use Sysmon for process creation events tied to firewall commands or scripts (Sysmon Event ID 1). - Linux Firewall Logs: Use auditd to track commands like iptables, firewalld, or ufw: `auditctl -a always,exit -F arch=b64 -S execve -k firewall_disable` - macOS Firewall: Monitor changes to the macOS Application Firewall using the log show command. Network-Level Monitoring - IDS/IPS Alerts: Deploy IDS/IPS systems to monitor abnormal traffic flows that could indicate firewall disablement. - NetFlow Data: Analyze NetFlow or packet capture data for traffic patterns inconsistent with firewall enforcement. SIEM and CSPM Tools - SIEM Integration: Use tools like Splunk or QRadar to centralize and analyze firewall disablement events from both hosts and cloud platforms. - Cloud Security Posture Management (CSPM): Use CSPM solutions to monitor misconfigurations and track deactivation of critical cloud services like firewalls.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0043](https://attack.mitre.org/datacomponents/DC0043)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
