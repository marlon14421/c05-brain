---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0139"
target_object: "T1083"
stix_relationship_id: "relationship--24ea53e3-a51f-4c4a-b3de-2e1d09ed69e8"
---
# Relationship 9935: S0139 — uses → T1083

**Source object:** [[01 ATT&CK/S0139 - PowerDuke|S0139: PowerDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerDuke](https://attack.mitre.org/software/S0139) has commands to get the current directory name as well as the size of a file. It also has commands to obtain information about logical drives, drive type, and free space.(Citation: Volexity PowerDuke November 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--24ea53e3-a51f-4c4a-b3de-2e1d09ed69e8`.
