---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0632"
target_object: "T1106"
stix_relationship_id: "relationship--6abe4e38-5d96-469e-b648-dca7a520cc2e"
---
# Relationship 5166: S0632 — uses → T1106

**Source object:** [[01 ATT&CK/S0632 - GrimAgent|S0632: GrimAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GrimAgent](https://attack.mitre.org/software/S0632) can use Native API including GetProcAddress and ShellExecuteW .(Citation: Group IB GrimAgent July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6abe4e38-5d96-469e-b648-dca7a520cc2e`.
