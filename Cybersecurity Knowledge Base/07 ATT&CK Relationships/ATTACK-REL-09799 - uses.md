---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1070.004"
stix_relationship_id: "relationship--dffbef04-c1bb-4289-98f6-8f318cbfe44a"
---
# Relationship 9799: S1246 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has deleted files from a compromised host after they were exfiltrated.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dffbef04-c1bb-4289-98f6-8f318cbfe44a`.
