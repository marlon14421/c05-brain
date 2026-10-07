---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0058"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0058: Snapshot Modification — Defensive Application

## Source record

- [[01 ATT&CK/DC0058 - Snapshot Modification|DC0058 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

Changes made to a cloud snapshot's metadata, attributes, or control settings. These modifications may involve adjusting access permissions, changing retention policies, or altering encryption settings. *Data Collection Measures:* - AWS CloudTrail - Tracks API calls such as `ModifySnapshotAttribute`, `ResetSnapshotAttribute`, and `ModifySnapshotTier`. - Azure Monitor Logs - Logs changes via `Microsoft.Compute/snapshots/write`. - Google Cloud Logging - Captures modifications through `compute.snapshots.setIamPolicy` and `compute.snapshots.patch`.

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
