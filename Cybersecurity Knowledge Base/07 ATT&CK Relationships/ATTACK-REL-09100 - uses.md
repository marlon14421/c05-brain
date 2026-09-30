---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1070.004"
stix_relationship_id: "relationship--f34665d9-96d4-4c11-92a8-b2f1d4945a50"
---
# Relationship 9100: S1242 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can delete itself from infected hosts after execution.(Citation: Halcyon Qilin.B OCT 2024)(Citation: Sophos Qilin MSP APR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f34665d9-96d4-4c11-92a8-b2f1d4945a50`.
