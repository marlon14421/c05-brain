---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1049"
stix_relationship_id: "relationship--fe892807-f2da-4fc2-a552-979a10c44094"
---
# Relationship 5205: G1032 — uses → T1049

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has used RDP to test network connections.(Citation: SOCRadar INC Ransom January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe892807-f2da-4fc2-a552-979a10c44094`.
