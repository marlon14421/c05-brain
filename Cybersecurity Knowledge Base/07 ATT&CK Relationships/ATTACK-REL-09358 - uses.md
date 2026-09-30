---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1069"
stix_relationship_id: "relationship--982751f5-40e1-4f10-a926-2c016393c652"
---
# Relationship 9358: G1015 — uses → T1069

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has enumerated the vSphere Admins and ESX Admins groups in targeted environments.(Citation: Mandiant VMware vSphere JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--982751f5-40e1-4f10-a926-2c016393c652`.
