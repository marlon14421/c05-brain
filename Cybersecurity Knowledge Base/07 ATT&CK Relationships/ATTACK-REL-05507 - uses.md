---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1556.006"
stix_relationship_id: "relationship--55e1a1e9-689f-4242-8316-d59c309849d6"
---
# Relationship 5507: G1015 — uses → T1556.006

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556.006 - Multi-Factor Authentication|T1556.006: Multi-Factor Authentication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After compromising user accounts, [Scattered Spider](https://attack.mitre.org/groups/G1015) registers their own MFA tokens.(Citation: CISA Scattered Spider Advisory November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55e1a1e9-689f-4242-8316-d59c309849d6`.
