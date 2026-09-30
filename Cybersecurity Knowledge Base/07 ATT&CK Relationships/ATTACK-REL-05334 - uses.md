---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0042"
target_object: "T1585.003"
stix_relationship_id: "relationship--9237a0b7-99a9-4902-a74f-7d7958d5bec6"
---
# Relationship 5334: C0042 — uses → T1585.003

**Source object:** [[01 ATT&CK/C0042 - Outer Space|C0042: Outer Space]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.003 - Cloud Accounts|T1585.003: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Outer Space](https://attack.mitre.org/campaigns/C0042), [OilRig](https://attack.mitre.org/groups/G0049) created M365 email accounts to be used as part of C2.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9237a0b7-99a9-4902-a74f-7d7958d5bec6`.
