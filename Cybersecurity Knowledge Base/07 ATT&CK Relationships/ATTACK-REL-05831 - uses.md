---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0366"
target_object: "T1047"
stix_relationship_id: "relationship--6ad5d5c8-b53e-417c-a574-3818269d1e85"
---
# Relationship 5831: S0366 — uses → T1047

**Source object:** [[01 ATT&CK/S0366 - WannaCry|S0366: WannaCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WannaCry](https://attack.mitre.org/software/S0366) utilizes wmic to delete shadow copies.(Citation: LogRhythm WannaCry)(Citation: FireEye WannaCry 2017)(Citation: SecureWorks WannaCry Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ad5d5c8-b53e-417c-a574-3818269d1e85`.
