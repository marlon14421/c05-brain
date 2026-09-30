---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0282"
target_object: "T1070.004"
stix_relationship_id: "relationship--08b4b3f1-3c20-4e70-8a42-99fd5f191b12"
---
# Relationship 3840: S0282 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0282 - MacSpy|S0282: MacSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MacSpy](https://attack.mitre.org/software/S0282) deletes any temporary files it creates(Citation: alientvault macspy)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08b4b3f1-3c20-4e70-8a42-99fd5f191b12`.
