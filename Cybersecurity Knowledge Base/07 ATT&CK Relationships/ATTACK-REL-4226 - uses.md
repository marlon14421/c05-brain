---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0695"
target_object: "T1027.002"
stix_relationship_id: "relationship--60d3d7d8-408e-4663-b081-69fe66303983"
---
# Relationship 4226: S0695 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0695 - Donut|S0695: Donut]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Donut](https://attack.mitre.org/software/S0695) can generate packed code modules.(Citation: Donut Github)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60d3d7d8-408e-4663-b081-69fe66303983`.
