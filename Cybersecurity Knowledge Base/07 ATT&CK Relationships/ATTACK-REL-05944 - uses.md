---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0053"
target_object: "T1059.003"
stix_relationship_id: "relationship--0191f3d3-59d3-4fcc-bfff-5fbfa0675cfd"
---
# Relationship 5944: S0053 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0053 - SeaDuke|S0053: SeaDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SeaDuke](https://attack.mitre.org/software/S0053) is capable of executing commands.(Citation: Unit 42 SeaDuke 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0191f3d3-59d3-4fcc-bfff-5fbfa0675cfd`.
