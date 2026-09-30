---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1184"
target_object: "T1070.004"
stix_relationship_id: "relationship--bcda4232-e09c-4bed-a4a6-09e38f8a0056"
---
# Relationship 5878: S1184 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1184 - BOLDMOVE|S1184: BOLDMOVE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) can remove files on victim systems.(Citation: Google Cloud BOLDMOVE 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bcda4232-e09c-4bed-a4a6-09e38f8a0056`.
