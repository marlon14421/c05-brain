---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "T1087.002"
stix_relationship_id: "relationship--d317032f-75dc-4d73-95ec-eabf3ed9d947"
---
# Relationship 8464: G1046 — uses → T1087.002

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has performed domain account enumeration during intrusions.(Citation: Microsoft Storm-1811 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d317032f-75dc-4d73-95ec-eabf3ed9d947`.
