---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0051"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0051: Firewall Rule Modification — Defensive Application

## Source record

- [[01 ATT&CK/DC0051 - Firewall Rule Modification|DC0051 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The creation, deletion, or alteration of firewall rules to allow or block specific network traffic. Monitoring changes to these rules is critical for detecting misconfigurations, unauthorized access, or malicious attempts to bypass network protections. Examples: - Rule Creation: Adding a new rule to allow inbound traffic on port 3389 (RDP). - Rule Deletion: Deleting a rule that blocks inbound traffic from untrusted IP ranges. - Rule Modification: Changing a rule to allow traffic from "any" source IP instead of a specific trusted range. - Audit Log Metadata: Logs indicating "Firewall rule modified by admin@domain.com." - Platform-Specific Scenarios - Azure: Altering rules in an Azure Network Security Group (NSG). - AWS: Modifying Security Group rules to allow traffic. - Windows: Changes tracked in Security Event Logs (EID 4950 or 4951). This data component can be collected through the following measures: Cloud Control Plane - Azure: Collect rule modification logs from Azure Firewall Activity Logs. - Example Command: `az network firewall policy rule-collection-group rule-collection list --policy-name ` - AWS: Use CloudTrail to track `AuthorizeSecurityGroupIngress` or `RevokeSecurityGroupIngress` actions. Example: `aws ec2 describe-security-groups` - Google Cloud: Use gcloud commands to extract firewall rules: `gcloud compute firewall-rules list --format=json` Host-Based Firewalls - Windows: - Collect events from the Windows Security Event Log (EID 4950: A rule has been modified). - Use PowerShell to track rule changes: `Get-NetFirewallRule -PolicyStore PersistentStore` - Linux: - Monitor iptables or nftables rule modifications: `iptables -L -v` - Use auditd for real-time monitoring: `auditctl -w /etc/iptables.rules -p wa` - macOS: Use pfctl to monitor rule changes: `sudo pfctl -sr` SIEM Integration - Collect logs from cloud platforms, host systems, and network appliances for centralized monitoring. API Monitoring - Monitor API calls for firewall rule modifications.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
