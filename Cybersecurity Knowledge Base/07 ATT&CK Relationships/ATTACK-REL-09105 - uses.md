---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0364"
target_object: "T1561.001"
stix_relationship_id: "relationship--7fa1a7c8-0dfb-4bd5-a34f-509ba24da5be"
---
# Relationship 9105: S0364 — uses → T1561.001

**Source object:** [[01 ATT&CK/S0364 - RawDisk|S0364: RawDisk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RawDisk](https://attack.mitre.org/software/S0364) has been used to directly access the hard disk to help overwrite arbitrarily sized portions of disk content.(Citation: Novetta Blockbuster Destructive Malware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fa1a7c8-0dfb-4bd5-a34f-509ba24da5be`.
