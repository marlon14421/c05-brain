---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0415"
target_object: "T1129"
stix_relationship_id: "relationship--db3b37f1-9c85-4e52-bbd7-4b71ad68400d"
---
# Relationship 7138: S0415 — uses → T1129

**Source object:** [[01 ATT&CK/S0415 - BOOSTWRITE|S0415: BOOSTWRITE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOOSTWRITE](https://attack.mitre.org/software/S0415) has used the DWriteCreateFactory() function to load additional modules.(Citation: FireEye FIN7 Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db3b37f1-9c85-4e52-bbd7-4b71ad68400d`.
