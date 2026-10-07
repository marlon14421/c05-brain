---
tags:
  - cybersecurity
  - defensive-security
  - attack-relationship-review
relationship_type: "subtechnique-of"
source_object: "T1055.012"
target_object: "T1055"
---
# ATTACK-REL-2392 - subtechnique-of: subtechnique-of relationship

## Source relationship

- [[07 ATT&CK Relationships/ATTACK-REL-2392 - subtechnique-of|Open relationship card]]
- Source object: `T1055.012`
- Relationship: `subtechnique-of`
- Target object: `T1055`
- STIX relationship: `relationship--1d79747d-3ff5-44ab-ae40-80823347c7d7`

## Defensive interpretation

This edge expresses ATT&CK hierarchy: a sub-technique is a more specific form of a parent technique. Preserve this direction and inspect both records for scope and platform context.

## Review checklist

- Which behavior is shared with the parent and what condition makes the sub-technique distinct?
- Does local asset inventory include the relevant platform and configuration?
- Are detections and mitigations mapped at the right level without double-counting coverage?
- What evidence would distinguish this behavior from the broader parent category?
- Are source records current and applicable to the system version?

## Safe validation

Use documentation review, a local lab, or benign telemetry. Avoid assuming that a parent-level association proves a sub-technique is present. Define scope, owner, time window, evidence needs, and stop conditions before testing. Prefer configuration review, tabletop exercises, and isolated labs. Do not access unauthorized systems or collect real sensitive data.

## Decision record

Record source version, environment, applicability, evidence, confidence, exceptions, and owner. Keep observations separate from interpretation. Verify the control or analytic with a measurable test and document remaining coverage gaps.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
