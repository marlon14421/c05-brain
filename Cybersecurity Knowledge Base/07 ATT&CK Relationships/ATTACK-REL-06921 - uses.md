---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1135"
stix_relationship_id: "relationship--7d7e63bb-1b78-459d-a300-d21bb270ad7d"
---
# Relationship 6921: C0014 — uses → T1135

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors discovered network disks mounted to the system using [netstat](https://attack.mitre.org/software/S0104).(Citation: FoxIT Wocao December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d7e63bb-1b78-459d-a300-d21bb270ad7d`.
