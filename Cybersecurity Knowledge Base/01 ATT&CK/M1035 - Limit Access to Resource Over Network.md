---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1035"
source_url: "https://attack.mitre.org/mitigations/M1035"
created: "2019-06-11"
modified: "2024-12-18"
---
# M1035: Limit Access to Resource Over Network

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1035  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Restrict access to network resources, such as file shares, remote systems, and services, to only those users, accounts, or systems with a legitimate business requirement. This can include employing technologies like network concentrators, RDP gateways, and zero-trust network access (ZTNA) models, alongside hardening services and protocols. This mitigation can be implemented through the following measures: Audit and Restrict Access: - Regularly audit permissions for file shares, network services, and remote access tools. - Remove unnecessary access and enforce least privilege principles for users and services. - Use Active Directory and IAM tools to restrict access based on roles and attributes. Deploy Secure Remote Access Solutions: - Use RDP gateways, VPN concentrators, and ZTNA solutions to aggregate and secure remote access connections. - Configure access controls to restrict connections based on time, device, and user identity. - Enforce MFA for all remote access mechanisms. Disable Unnecessary Services: - Identify running services using tools like netstat (Windows/Linux) or Nmap. - Disable unused services, such as Telnet, FTP, and legacy SMB, to reduce the attack surface. - Use firewall rules to block traffic on unused ports and protocols. Network Segmentation and Isolation: - Use VLANs, firewalls, or micro-segmentation to isolate critical network resources from general access. - Restrict communication between subnets to prevent lateral movement. Monitor and Log Access: - Monitor access attempts to file shares, RDP, and remote network resources using SIEM tools. - Enable auditing and logging for successful and failed attempts to access restricted resources. *Tools for Implementation* File Share Management: - Microsoft Active Directory Group Policies - Samba (Linux/Unix file share management) - AccessEnum (Windows access auditing tool) Secure Remote Access: - Microsoft Remote Desktop Gateway - Apache Guacamole (open-source RDP/VNC gateway) - Zero Trust solutions: Tailscale, Cloudflare Zero Trust Service and Protocol Hardening: - Nmap or Nessus for network service discovery - Windows Group Policy Editor for disabling SMBv1, Telnet, and legacy protocols - iptables or firewalld (Linux) for blocking unnecessary traffic Network Segmentation: - pfSense for open-source network isolation

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1035](https://attack.mitre.org/mitigations/M1035)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
