---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1229"
target_object: "T1059.001"
stix_relationship_id: "relationship--5420c4d7-41ff-40d0-9225-05ba7dfe48f3"
---
# Relationship 5384: S1229 — uses → T1059.001

**Source object:** [[01 ATT&CK/S1229 - Havoc|S1229: Havoc]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Havoc](https://attack.mitre.org/software/S1229) can facilitate the execution of PowerShell commands.(Citation: Immersive Labs Havoc C2 APR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5420c4d7-41ff-40d0-9225-05ba7dfe48f3`.
