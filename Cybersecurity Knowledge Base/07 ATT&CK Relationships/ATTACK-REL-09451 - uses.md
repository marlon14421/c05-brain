---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0513"
target_object: "T1070.004"
stix_relationship_id: "relationship--746c2da0-7ee6-4dd7-90b1-23c020cdb71d"
---
# Relationship 9451: S0513 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0513 - LiteDuke|S0513: LiteDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) can securely delete files by first writing random data to the file.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--746c2da0-7ee6-4dd7-90b1-23c020cdb71d`.
