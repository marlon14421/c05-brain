---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0026"
target_object: "T1070.004"
stix_relationship_id: "relationship--6175bbbe-1bc1-4562-8c5f-9e437348636a"
---
# Relationship 8518: G0026 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0026 - APT18|G0026: APT18]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT18](https://attack.mitre.org/groups/G0026) actors deleted tools and batch files from victim systems.(Citation: Dell Lateral Movement)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6175bbbe-1bc1-4562-8c5f-9e437348636a`.
