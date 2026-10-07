---
tags:
  - cybersecurity
  - defensive-security
  - attack-relationship-review
relationship_type: "mitigates"
source_object: "M1047"
target_object: "T1484.001"
---
# ATTACK-REL-1372 - mitigates: mitigates relationship

## Source relationship

- [[07 ATT&CK Relationships/ATTACK-REL-1372 - mitigates|Open relationship card]]
- Source object: `M1047`
- Relationship: `mitigates`
- Target object: `T1484.001`
- STIX relationship: `relationship--19e387c4-0dd8-4c00-9195-73ed25ad061e`

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
