---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0498"
target_object: "T1070.004"
stix_relationship_id: "relationship--67272019-b1e1-4c4e-8b7f-cd73b3ed6a31"
---
# Relationship 6410: S0498 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0498 - Cryptoistic|S0498: Cryptoistic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cryptoistic](https://attack.mitre.org/software/S0498) has the ability delete files from a compromised host.(Citation: SentinelOne Lazarus macOS July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67272019-b1e1-4c4e-8b7f-cd73b3ed6a31`.
