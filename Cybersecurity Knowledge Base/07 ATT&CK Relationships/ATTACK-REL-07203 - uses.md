---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1120"
stix_relationship_id: "relationship--d30d8fa0-7f24-41e5-ae8d-e4449e88d2f0"
---
# Relationship 7203: G0047 — uses → T1120

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) tools have contained an application to check performance of USB flash drives. [Gamaredon Group](https://attack.mitre.org/groups/G0047) has also used malware to scan for removable drives.(Citation: Palo Alto Gamaredon Feb 2017)(Citation: ESET Gamaredon June 2020)(Citation: ESET Gamaredon Sept2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d30d8fa0-7f24-41e5-ae8d-e4449e88d2f0`.
