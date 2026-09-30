---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "T1553.002"
stix_relationship_id: "relationship--eb4ce173-6f0e-4c12-9ff8-09c4fb1ae2d3"
---
# Relationship 8130: G1014 — uses → T1553.002

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LuminousMoth](https://attack.mitre.org/groups/G1014) has signed their malware with a valid digital signature.(Citation: Kaspersky LuminousMoth July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb4ce173-6f0e-4c12-9ff8-09c4fb1ae2d3`.
