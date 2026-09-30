---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1043"
target_object: "T1564.001"
stix_relationship_id: "relationship--7888f7bb-92a8-4c5a-abbc-6dcc4ad3e149"
---
# Relationship 5292: S1043 — uses → T1564.001

**Source object:** [[01 ATT&CK/S1043 - ccf32|S1043: ccf32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ccf32](https://attack.mitre.org/software/S1043) has created a hidden directory on targeted systems, naming it after the current local time (year, month, and day).(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7888f7bb-92a8-4c5a-abbc-6dcc4ad3e149`.
