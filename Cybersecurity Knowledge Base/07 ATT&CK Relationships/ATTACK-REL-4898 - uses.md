---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0345"
target_object: "T1105"
stix_relationship_id: "relationship--75f47e28-75dd-4471-8d00-ed4a2c4d3328"
---
# Relationship 4898: S0345 — uses → T1105

**Source object:** [[01 ATT&CK/S0345 - Seasalt|S0345: Seasalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Seasalt](https://attack.mitre.org/software/S0345) has a command to download additional files.(Citation: Mandiant APT1 Appendix)(Citation: Mandiant APT1 Appendix)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75f47e28-75dd-4471-8d00-ed4a2c4d3328`.
