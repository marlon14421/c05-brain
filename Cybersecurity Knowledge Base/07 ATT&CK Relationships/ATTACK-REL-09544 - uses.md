---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0241"
target_object: "T1087.001"
stix_relationship_id: "relationship--7d181964-875f-4132-8882-46e9dd18e893"
---
# Relationship 9544: S0241 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0241 - RATANKBA|S0241: RATANKBA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RATANKBA](https://attack.mitre.org/software/S0241) uses the net user command.(Citation: RATANKBA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d181964-875f-4132-8882-46e9dd18e893`.
