---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1199"
target_object: "T1021.002"
stix_relationship_id: "relationship--c8b6114c-df7f-4e19-ae9f-6cde01c46b04"
---
# Relationship 9612: S1199 — uses → T1021.002

**Source object:** [[01 ATT&CK/S1199 - LockBit 2.0|S1199: LockBit 2.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) has the ability to move laterally via SMB.(Citation: Palo Alto Lockbit 2.0 JUN 2022)(Citation: SentinelOne LockBit 2.0)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8b6114c-df7f-4e19-ae9f-6cde01c46b04`.
