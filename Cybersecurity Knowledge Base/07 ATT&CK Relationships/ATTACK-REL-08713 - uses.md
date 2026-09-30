---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0085"
target_object: "T1070.004"
stix_relationship_id: "relationship--7bbe8987-5cb2-464d-8874-56825164313c"
---
# Relationship 8713: S0085 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0085 - S-Type|S0085: S-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[S-Type](https://attack.mitre.org/software/S0085) has deleted files it has created on a compromised host.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7bbe8987-5cb2-464d-8874-56825164313c`.
