---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1212"
target_object: "T1059.001"
stix_relationship_id: "relationship--00fe415d-9364-4d03-95ee-f1413d996c30"
---
# Relationship 9308: S1212 — uses → T1059.001

**Source object:** [[01 ATT&CK/S1212 - RansomHub|S1212: RansomHub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) can use PowerShell to delete volume shadow copies.(Citation: Group-IB RansomHub FEB 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00fe415d-9364-4d03-95ee-f1413d996c30`.
