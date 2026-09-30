---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1570"
stix_relationship_id: "relationship--427a272e-4500-4216-8816-a6c7d4492f3e"
---
# Relationship 2923: S0532 — uses → T1570

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) can use [certutil](https://attack.mitre.org/software/S0160) for propagation on Windows hosts within intranets.(Citation: Unit 42 Lucifer June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--427a272e-4500-4216-8816-a6c7d4492f3e`.
