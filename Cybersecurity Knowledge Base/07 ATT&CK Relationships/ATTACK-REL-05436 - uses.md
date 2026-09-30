---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0046"
target_object: "T1014"
stix_relationship_id: "relationship--9f9d3b11-4b0e-4e56-b19f-62e80ce0ada9"
---
# Relationship 5436: C0046 — uses → T1014

**Source object:** [[01 ATT&CK/C0046 - ArcaneDoor|C0046: ArcaneDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ArcaneDoor](https://attack.mitre.org/campaigns/C0046) included hooking the `processHostScanReply()` function on victim Cisco ASA devices.(Citation: Cisco ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f9d3b11-4b0e-4e56-b19f-62e80ce0ada9`.
