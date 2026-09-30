---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1135"
target_object: "T1070.006"
stix_relationship_id: "relationship--d8ea50e5-0e68-4253-a922-61b549c40778"
---
# Relationship 8523: S1135 — uses → T1070.006

**Source object:** [[01 ATT&CK/S1135 - MultiLayer Wiper|S1135: MultiLayer Wiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MultiLayer Wiper](https://attack.mitre.org/software/S1135) changes timestamps of overwritten files to either 1601.1.1 for NTFS filesystems, or 1980.1.1 for all other filesystems.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8ea50e5-0e68-4253-a922-61b549c40778`.
