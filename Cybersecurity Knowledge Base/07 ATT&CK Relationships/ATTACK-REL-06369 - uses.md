---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1560.003"
stix_relationship_id: "relationship--0f3af4de-b1cc-4cc2-9eb7-9aa46cdebfcd"
---
# Relationship 6369: S0038 — uses → T1560.003

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Modules can be pushed to and executed by [Duqu](https://attack.mitre.org/software/S0038) that copy data to a staging area, compress it, and XOR encrypt it.(Citation: Symantec W32.Duqu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f3af4de-b1cc-4cc2-9eb7-9aa46cdebfcd`.
