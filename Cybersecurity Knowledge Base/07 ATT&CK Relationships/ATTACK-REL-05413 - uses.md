---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1564.005"
stix_relationship_id: "relationship--150e1b1c-a575-4542-a66e-c1646212744b"
---
# Relationship 5413: S0126 — uses → T1564.005

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.005 - Hidden File System|T1564.005: Hidden File System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) has used a portable FAT16 partition image placed in %TEMP% as a hidden file system.(Citation: ESET ComRAT May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--150e1b1c-a575-4542-a66e-c1646212744b`.
