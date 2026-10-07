---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0068"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0068: Active Directory Object Deletion — Defensive Application

## Source record

- [[01 ATT&CK/DC0068 - Active Directory Object Deletion|DC0068 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Object deletion in AD (e.g., user accounts, groups, OUs) is logged as Event ID 5141. Examples: - User Account: Deleted user. - Group: Deleted security/distribution group. - Organizational Unit (OU): Loss of configurations or policies. - Service Account: Disrupted operations or cover tracks. - Trust Object: Removed domain trust, disrupting connectivity. *Data Collection Measures:* - Audit Policy: - Enable "Audit Directory Service Changes" (Success and Failure). - Path: `Computer Configuration > Policies > Windows Settings > Security Settings > Advanced Audit Policy Configuration > Audit Policies > Directory Service Changes`. - Key Event: Event ID 5141. - Log Forwarding: Use WEF to centralize logs for SIEM tools (e.g., Splunk). - Enable EDR Monitoring: - Detect processes or users that initiate unauthorized object deletions. - Monitor tools and scripts that may delete key directory objects.

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
