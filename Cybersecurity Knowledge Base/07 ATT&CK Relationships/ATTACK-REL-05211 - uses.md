---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1199"
target_object: "T1484.001"
stix_relationship_id: "relationship--78ecd98e-4235-4672-9e07-834c39542b6d"
---
# Relationship 5211: S1199 — uses → T1484.001

**Source object:** [[01 ATT&CK/S1199 - LockBit 2.0|S1199: LockBit 2.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1484.001 - Group Policy Modification|T1484.001: Group Policy Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) can modify Group Policy to disable Windows Defender and to automatically infect devices in Windows domains.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Palo Alto Lockbit 2.0 JUN 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78ecd98e-4235-4672-9e07-834c39542b6d`.
