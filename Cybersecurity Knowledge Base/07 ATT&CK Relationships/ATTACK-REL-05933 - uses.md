---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0013"
target_object: "T1059.005"
stix_relationship_id: "relationship--ada86d8c-2c88-442d-8f7a-d9e53937a3f2"
---
# Relationship 5933: C0013 — uses → T1059.005

**Source object:** [[01 ATT&CK/C0013 - Operation Sharpshooter|C0013: Operation Sharpshooter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013), the threat actors used a VBA macro to execute a simple downloader that installed [Rising Sun](https://attack.mitre.org/software/S0448).(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ada86d8c-2c88-442d-8f7a-d9e53937a3f2`.
