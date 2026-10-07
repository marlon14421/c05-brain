---
tags:
  - cybersecurity
  - defensive-security
  - attack-relationship-review
relationship_type: "attributed-to"
source_object: "C0038"
target_object: "G1055"
---
# ATTACK-REL-2645 - attributed-to: attributed-to relationship

## Source relationship

- [[07 ATT&CK Relationships/ATTACK-REL-2645 - attributed-to|Open relationship card]]
- Source object: `C0038`
- Relationship: `attributed-to`
- Target object: `G1055`
- STIX relationship: `relationship--0dd04e16-ad64-4b7d-af2f-12ad644cfe3e`

## Defensive interpretation

This edge records a catalog attribution between a campaign and a threat group. Attribution is an analytic judgment with uncertainty, not proof that a particular actor conducted a local event.

## Review checklist

- What original sources support the relationship and how strong is the corroboration?
- Are alternative explanations, shared infrastructure, or naming differences considered?
- Which observable behaviors matter to local defensive decisions independent of attribution?
- Does the confidence level change response, notification, or risk treatment proportionately?
- Are source dates and caveats preserved in any downstream report?

## Safe validation

Use the edge as contextual intelligence only. Do not attribute a local incident from a catalog link; preserve evidence and communicate uncertainty. Define scope, owner, time window, evidence needs, and stop conditions before testing. Prefer configuration review, tabletop exercises, and isolated labs. Do not access unauthorized systems or collect real sensitive data.

## Decision record

Record source version, environment, applicability, evidence, confidence, exceptions, and owner. Keep observations separate from interpretation. Verify the control or analytic with a measurable test and document remaining coverage gaps.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
