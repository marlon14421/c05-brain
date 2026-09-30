---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0366"
target_object: "T1563.002"
stix_relationship_id: "relationship--6b22c256-44a9-4b73-8df6-e4da9c32a5a3"
---
# Relationship 6220: S0366 — uses → T1563.002

**Source object:** [[01 ATT&CK/S0366 - WannaCry|S0366: WannaCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1563.002 - RDP Hijacking|T1563.002: RDP Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WannaCry](https://attack.mitre.org/software/S0366) enumerates current remote desktop sessions and tries to execute the malware on each session.(Citation: LogRhythm WannaCry)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b22c256-44a9-4b73-8df6-e4da9c32a5a3`.
