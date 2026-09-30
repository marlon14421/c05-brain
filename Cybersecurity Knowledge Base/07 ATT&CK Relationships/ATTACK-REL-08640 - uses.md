---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0452"
target_object: "T1049"
stix_relationship_id: "relationship--e6cd4568-3c15-4d1d-ab2c-c799141cf34b"
---
# Relationship 8640: S0452 — uses → T1049

**Source object:** [[01 ATT&CK/S0452 - USBferry|S0452: USBferry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[USBferry](https://attack.mitre.org/software/S0452) can use netstat and nbtstat to detect active network connections.(Citation: TrendMicro Tropic Trooper May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6cd4568-3c15-4d1d-ab2c-c799141cf34b`.
