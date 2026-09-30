---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1064"
target_object: "T1036.004"
stix_relationship_id: "relationship--15563e89-85cc-4092-a359-4351999bb9f3"
---
# Relationship 5979: S1064 — uses → T1036.004

**Source object:** [[01 ATT&CK/S1064 - SVCReady|S1064: SVCReady]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SVCReady](https://attack.mitre.org/software/S1064) has named a task `RecoveryExTask` as part of its persistence activity.(Citation: HP SVCReady Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15563e89-85cc-4092-a359-4351999bb9f3`.
