---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0366"
target_object: "T1222.001"
stix_relationship_id: "relationship--c49a3d89-c8fa-4c5d-813e-f4495d892d1a"
---
# Relationship 6909: S0366 — uses → T1222.001

**Source object:** [[01 ATT&CK/S0366 - WannaCry|S0366: WannaCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1222.001 - Windows Permissions|T1222.001: Windows Permissions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WannaCry](https://attack.mitre.org/software/S0366) uses attrib +h and icacls . /grant Everyone:F /T /C /Q to make some of its files hidden and grant all users full access controls.(Citation: LogRhythm WannaCry)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c49a3d89-c8fa-4c5d-813e-f4495d892d1a`.
