---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1012"
target_object: "T1059.001"
stix_relationship_id: "relationship--dd909ab4-9160-4194-9213-7478189936e0"
---
# Relationship 6279: G1012 — uses → T1059.001

**Source object:** [[01 ATT&CK/G1012 - CURIUM|G1012: CURIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CURIUM](https://attack.mitre.org/groups/G1012) has leveraged PowerShell scripts for initial process execution and data gathering in victim environments.(Citation: Symantec Tortoiseshell 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd909ab4-9160-4194-9213-7478189936e0`.
