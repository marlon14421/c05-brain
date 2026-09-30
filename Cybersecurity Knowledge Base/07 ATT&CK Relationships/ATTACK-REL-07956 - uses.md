---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1198"
target_object: "T1018"
stix_relationship_id: "relationship--5fe7e204-803e-47fc-83a5-f4766d2cedfa"
---
# Relationship 7956: S1198 — uses → T1018

**Source object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) probes arbitrary network endpoints for TCP connectivity.(Citation: Symantec Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5fe7e204-803e-47fc-83a5-f4766d2cedfa`.
