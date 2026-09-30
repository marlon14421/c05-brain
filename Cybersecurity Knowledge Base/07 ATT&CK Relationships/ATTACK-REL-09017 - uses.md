---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0350"
target_object: "T1053.005"
stix_relationship_id: "relationship--38419f2f-51d2-47ed-9fd9-bba3712474cc"
---
# Relationship 9017: S0350 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0350 - zwShell|S0350: zwShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[zwShell](https://attack.mitre.org/software/S0350) has used SchTasks for execution.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38419f2f-51d2-47ed-9fd9-bba3712474cc`.
