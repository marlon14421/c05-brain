---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "S1198"
stix_relationship_id: "relationship--87bbe119-1a77-4686-ab3a-bdc116fb721a"
---
# Relationship 4400: G0094 — uses → S1198

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) is uniquely associated with [Kimsuky](https://attack.mitre.org/groups/G0094) operations.(Citation: Symantec Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87bbe119-1a77-4686-ab3a-bdc116fb721a`.
