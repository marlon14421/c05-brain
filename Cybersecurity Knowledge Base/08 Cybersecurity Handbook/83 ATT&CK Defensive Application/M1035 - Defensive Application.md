---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1035"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1035: Limit Access to Resource Over Network — Defensive Application

## Source record

- [[01 ATT&CK/M1035 - Limit Access to Resource Over Network|M1035 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Restrict access to network resources, such as file shares, remote systems, and services, to only those users, accounts, or systems with a legitimate business requirement. This can include employing technologies like network concentrators, RDP gateways, and zero-trust network access (ZTNA) models, alongside hardening services and protocols. This mitigation can be implemented through the following measures: Audit and Restrict Access: - Regularly audit permissions for file shares, network services, and remote access tools. - Remove unnecessary access and enforce least privilege principles for users and services. - Use Active Directory and IAM tools to restrict access based on roles and attributes. Deploy Secure Remote Access Solutions: - Use RDP gateways, VPN concentrators, and ZTNA solutions to aggregate and secure remote access connections. - Configure access controls to restrict connections based on time, device, and user identity. - Enforce MFA for all remote access mechanisms. Disable Unnecessary Services: - Identify running services using tools like netstat (Windows/Linux) or Nmap. - Disable unused services, such as Telnet, FTP, and legacy SMB, to reduce the attack surface. - Use firewall rules to block traffic on unused ports and protocols. Network Segmentation and Isolation: - Use VLANs, firewalls, or micro-segmentation to isolate critical network resources from general access. - Restrict communication between subnets to prevent lateral movement. Monitor and Log Access: - Monitor access attempts to file shares, RDP, and remote network resources using SIEM tools. - Enable auditing and logging for successful and failed attempts to access restricted resources. *Tools for Implementation* File Share Management: - Microsoft Active Directory Group Policies - Samba (Linux/Unix file share management) - AccessEnum (Windows access auditing tool) Secure Remote Access: - Microsoft Remote Desktop Gateway - Apache Guacamole (open-source RDP/VNC gateway) - Zero Trust solutions: Tailscale, Cloudflare Zero Trust Service and Protocol Hardening: - Nmap or Nessus for network service discovery - Windows Group Policy Editor for disabling SMBv1, Telnet, and legacy protocols - iptables or firewalld (Linux) for blocking unnecessary traffic Network Segmentation: - pfSense for open-source network isolation

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
