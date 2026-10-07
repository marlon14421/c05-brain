---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0098"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0098: Volume Deletion — Defensive Application

## Source record

- [[01 ATT&CK/DC0098 - Volume Deletion|DC0098 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The removal of a cloud-based or on-premise block storage volume. This action permanently deletes the allocated storage and may result in data loss if not backed up. *Data Collection Measures:* - Cloud Logging & APIs - AWS CloudTrail Logs - `eventName: DeleteVolume` (tracks volume deletions) - Azure Monitor Logs - `operationName: Microsoft.Compute/disks/delete` - `status: Success | Failure` (flag unauthorized delete attempts) - Google Cloud Audit Logs - `protoPayload.methodName: "v1.compute.disks.delete"` - `authenticationInfo.principalEmail` (identifies the user deleting the volume) - System & Host-Based Logging - Linux & macOS Logs: - `/var/log/syslog` or `/var/log/messages` for volume detach/deletion actions - Windows Event Logs: - Event ID 98 (Storage Class Memory) - Event ID 225 (Volume Removal Detected) - Event ID 12 (Disk Removal Notification)

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
