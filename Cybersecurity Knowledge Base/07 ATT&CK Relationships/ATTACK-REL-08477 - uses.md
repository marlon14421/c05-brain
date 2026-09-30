---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1070.004"
stix_relationship_id: "relationship--2b4a8be2-8403-43d4-addd-79c504e3dec8"
---
# Relationship 8477: S0125 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remsec](https://attack.mitre.org/software/S0125) is capable of deleting files on the victim. It also securely removes itself after collecting and exfiltrating data.(Citation: Symantec Remsec IOCs)(Citation: Kaspersky ProjectSauron Full Report)(Citation: Kaspersky ProjectSauron Technical Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b4a8be2-8403-43d4-addd-79c504e3dec8`.
