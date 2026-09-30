---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0127"
target_object: "T1070.004"
stix_relationship_id: "relationship--93812c9c-39f1-4bf6-adda-601d0ffd88bf"
---
# Relationship 8006: S0127 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0127 - BBSRAT|S0127: BBSRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BBSRAT](https://attack.mitre.org/software/S0127) can delete files and directories.(Citation: Palo Alto Networks BBSRAT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93812c9c-39f1-4bf6-adda-601d0ffd88bf`.
