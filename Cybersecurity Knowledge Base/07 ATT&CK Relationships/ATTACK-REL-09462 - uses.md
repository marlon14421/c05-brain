---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1070.004"
stix_relationship_id: "relationship--6e6a6314-8549-4ffa-890a-825b164cdb51"
---
# Relationship 9462: G1052 — uses → T1070.004

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has configured malware to remove archives used in collection activities following successful exfiltration.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e6a6314-8549-4ffa-890a-825b164cdb51`.
