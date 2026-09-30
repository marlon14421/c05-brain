---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1059.001"
stix_relationship_id: "relationship--bdac1391-310e-4511-b272-b80924166723"
---
# Relationship 8547: S0126 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) has used PowerShell to load itself every time a user logs in to the system. [ComRAT](https://attack.mitre.org/software/S0126) can execute PowerShell scripts loaded into memory or from the file system.(Citation: ESET ComRAT May 2020)(Citation: CISA ComRAT Oct 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bdac1391-310e-4511-b272-b80924166723`.
