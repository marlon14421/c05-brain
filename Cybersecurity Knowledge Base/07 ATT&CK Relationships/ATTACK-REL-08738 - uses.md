---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1021.007"
stix_relationship_id: "relationship--e8d5e9f3-ec32-4a07-bdc7-86a2cff8a975"
---
# Relationship 8738: G1015 — uses → T1021.007

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.007 - Cloud Services|T1021.007: Cloud Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has also leveraged pre-existing AWS EC2 instances for lateral movement and data collection purposes.(Citation: CISA Scattered Spider Advisory November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e8d5e9f3-ec32-4a07-bdc7-86a2cff8a975`.
