---
tags:
  - cybersecurity
  - defensive-security
  - attack-relationship-review
relationship_type: "mitigates"
source_object: "M1013"
target_object: "T1496.003"
---
# ATTACK-REL-1212 - mitigates: mitigates relationship

## Source relationship

- [[07 ATT&CK Relationships/ATTACK-REL-1212 - mitigates|Open relationship card]]
- Source object: `M1013`
- Relationship: `mitigates`
- Target object: `T1496.003`
- STIX relationship: `relationship--1bdf5794-9f6f-4d9a-9afd-542cefa858d0`

## Defensive interpretation

This edge links a mitigation to a behavior it is intended to reduce. Confirm that the safeguard is available, correctly configured, owned, and appropriate to the local environment.

## Review checklist

- Which assets and versions need this control, and who owns deployment?
- Does the control reduce the relevant exposure without breaking legitimate workflows?
- What coverage gaps, exceptions, and compensating controls remain?
- How can configuration drift or bypass be detected?
- What benign test demonstrates effectiveness and safe rollback?

## Safe validation

Pilot the control in a representative lab or approved test group. Use benign behavior and synthetic data; coordinate any production change with the owner. Define scope, owner, time window, evidence needs, and stop conditions before testing. Prefer configuration review, tabletop exercises, and isolated labs. Do not access unauthorized systems or collect real sensitive data.

## Decision record

Record source version, environment, applicability, evidence, confidence, exceptions, and owner. Keep observations separate from interpretation. Verify the control or analytic with a measurable test and document remaining coverage gaps.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
