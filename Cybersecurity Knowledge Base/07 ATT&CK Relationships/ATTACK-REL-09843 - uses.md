---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0365"
target_object: "T1016"
stix_relationship_id: "relationship--039364a9-2afd-4ae5-9df0-08d4e583674f"
---
# Relationship 9843: S0365 — uses → T1016

**Source object:** [[01 ATT&CK/S0365 - Olympic Destroyer|S0365: Olympic Destroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Olympic Destroyer](https://attack.mitre.org/software/S0365) uses API calls to enumerate the infected system's ARP table.(Citation: Talos Olympic Destroyer 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--039364a9-2afd-4ae5-9df0-08d4e583674f`.
