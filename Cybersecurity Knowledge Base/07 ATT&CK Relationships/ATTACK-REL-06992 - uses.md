---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0662"
target_object: "T1106"
stix_relationship_id: "relationship--7908bc8d-8a9b-48c0-897e-25266950b0da"
---
# Relationship 6992: S0662 — uses → T1106

**Source object:** [[01 ATT&CK/S0662 - RCSession|S0662: RCSession]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RCSession](https://attack.mitre.org/software/S0662) can use WinSock API for communication including WSASend and WSARecv .(Citation: Profero APT27 December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7908bc8d-8a9b-48c0-897e-25266950b0da`.
