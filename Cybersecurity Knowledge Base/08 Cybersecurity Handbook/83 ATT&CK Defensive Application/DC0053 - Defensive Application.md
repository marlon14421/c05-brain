---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0053"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0053: Firewall Metadata — Defensive Application

## Source record

- [[01 ATT&CK/DC0053 - Firewall Metadata|DC0053 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Contextual information about firewalls, including their configurations, policies, status, and other details such as names and associated rules. This metadata provides valuable insights into the operational state and configurations of firewalls, both in cloud control planes and host systems. Examples: - Firewall Name and Configuration: The name, type, and purpose of a firewall such as "Azure Firewall - Production Environment." - Policy Details: Capturing firewall policy details, such as "Allow inbound TCP 443 to web servers." - Firewall Status: Status indicators like "Active," "Disabled," or "Pending Updates." - Audit Log Metadata: Log entries showing administrative changes, such as "Policy modified by admin@domain.com." - Rules Associated with Firewalls: Rules specifying source/destination IP ranges, protocols, and ports. - Tagging Information: Tags like "Environment: Production" or "Owner: NetworkOps." This data component can be collected through the following measures: Cloud Control Plane - Azure: Use Azure Activity Logs and Network Watcher to collect metadata for Azure Firewall. - Example: `az network firewall show --name ` - AWS: Use AWS CloudTrail and describe commands: `aws ec2 describe-security-groups` - Google Cloud: Use gcloud commands to extract metadata: `gcloud compute firewall-rules list --format=json` Host-Based Firewalls - Windows: Use PowerShell to gather metadata: `Get-NetFirewallRule -PolicyStore PersistentStore` - Linux: Query iptables or nftables rulesets: `iptables -S` - macOS: Use pfctl to extract metadata: `sudo pfctl -sr` SIEM Integration - Collect logs from cloud platforms, host systems, and network appliances. API Monitoring - Monitor API calls for metadata requests. Example (AWS): `Capture DescribeSecurityGroups or DescribeNetworkAcls` calls via CloudTrail. Endpoint Detection and Response (EDR) - Use EDR solutions to monitor firewall management tools for configuration changes or queries.

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
