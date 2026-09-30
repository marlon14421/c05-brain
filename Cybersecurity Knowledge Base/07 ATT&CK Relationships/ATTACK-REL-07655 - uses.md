---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1083"
stix_relationship_id: "relationship--147e009d-48db-40bc-999c-70aa1e770a0c"
---
# Relationship 7655: S0125 — uses → T1083

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remsec](https://attack.mitre.org/software/S0125) is capable of listing contents of folders on the victim. [Remsec](https://attack.mitre.org/software/S0125) also searches for custom network encryption software on victims.(Citation: Symantec Remsec IOCs)(Citation: Kaspersky ProjectSauron Full Report)(Citation: Kaspersky ProjectSauron Technical Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--147e009d-48db-40bc-999c-70aa1e770a0c`.
