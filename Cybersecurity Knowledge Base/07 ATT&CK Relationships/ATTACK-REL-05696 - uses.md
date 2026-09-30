---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1083"
stix_relationship_id: "relationship--44356f01-27ae-45f5-b37f-85ce8c22fa44"
---
# Relationship 5696: G1054 — uses → T1083

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has run commands to check the content of folders on compromised hosts and has specifically targeted files with .doc, .ppt, .xls, .jtd, .eml, .xps, and .pdf extensions.(Citation: ESET MirrorFace DEC 2022)(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44356f01-27ae-45f5-b37f-85ce8c22fa44`.
