---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0690"
target_object: "T1070.004"
stix_relationship_id: "relationship--981bef7b-d442-487e-9763-1f69ffd71126"
---
# Relationship 8327: S0690 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0690 - Green Lambert|S0690: Green Lambert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Green Lambert](https://attack.mitre.org/software/S0690) can delete the original executable after initial installation in addition to unused functions.(Citation: Objective See Green Lambert for OSX Oct 2021)(Citation: Glitch-Cat Green Lambert ATTCK Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--981bef7b-d442-487e-9763-1f69ffd71126`.
