---
tags:
  - cybersecurity
  - defensive-security
  - attack-relationship-review
relationship_type: "detects"
source_object: "DET0133"
target_object: "T1219.001"
---
# ATTACK-REL-1457 - detects: detects relationship

## Source relationship

- [[07 ATT&CK Relationships/ATTACK-REL-1457 - detects|Open relationship card]]
- Source object: `DET0133`
- Relationship: `detects`
- Target object: `T1219.001`
- STIX relationship: `relationship--1c74bb94-725b-430e-a4f4-166fc9bcee7f`

## Defensive interpretation

This edge connects a detection object to behavior it may help identify. It does not show that local telemetry or an effective alert exists.

## Review checklist

- Are the required data sources enabled, retained, parsed, and mapped to the affected assets?
- Does the analytic distinguish this behavior from common administrative activity?
- Which benign simulation or sanitized event can verify expected signal and false positives?
- What is the response threshold and who may authorize containment?
- Which blind spots or version limits must be documented?

## Safe validation

Validate with synthetic events, benign simulations, or sanitized authorized data. Do not cause suspicious activity on third-party or production systems just to trigger an alert. Define scope, owner, time window, evidence needs, and stop conditions before testing. Prefer configuration review, tabletop exercises, and isolated labs. Do not access unauthorized systems or collect real sensitive data.

## Decision record

Record source version, environment, applicability, evidence, confidence, exceptions, and owner. Keep observations separate from interpretation. Verify the control or analytic with a measurable test and document remaining coverage gaps.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
