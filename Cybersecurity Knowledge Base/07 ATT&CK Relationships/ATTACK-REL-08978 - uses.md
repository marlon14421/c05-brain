---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1164"
target_object: "T1070.004"
stix_relationship_id: "relationship--9c8698db-cd08-479e-b155-f3eb280cc3bf"
---
# Relationship 8978: S1164 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) removes `bootstrap.min.css` after parsing command and control instructions, restoring the file to its original state.(Citation: Volexity UPSTYLE 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c8698db-cd08-479e-b155-f3eb280cc3bf`.
