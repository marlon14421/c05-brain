---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1070.004"
stix_relationship_id: "relationship--6d216f28-e5e1-4d73-abd9-b08f370f9d2b"
---
# Relationship 7043: S0689 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) can delete tools from a compromised host after execution.(Citation: Cisco Ukraine Wipers January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d216f28-e5e1-4d73-abd9-b08f370f9d2b`.
