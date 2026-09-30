---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0366"
target_object: "T1570"
stix_relationship_id: "relationship--fe78de3a-107f-4870-b5a1-c60289d68dec"
---
# Relationship 5920: S0366 — uses → T1570

**Source object:** [[01 ATT&CK/S0366 - WannaCry|S0366: WannaCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WannaCry](https://attack.mitre.org/software/S0366) attempts to copy itself to remote computers after gaining access via an SMB exploit.(Citation: LogRhythm WannaCry)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe78de3a-107f-4870-b5a1-c60289d68dec`.
