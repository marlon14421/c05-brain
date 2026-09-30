---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1584.005"
stix_relationship_id: "relationship--4f3415da-2f9f-41fb-bda3-0e154a9c33da"
---
# Relationship 7969: G0099 — uses → T1584.005

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.005 - Botnet|T1584.005: Botnet]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has used a botnet management interface to control large numbers of compromised hosts.(Citation: LevelBlue Blind Eagle Proton66 JUN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f3415da-2f9f-41fb-bda3-0e154a9c33da`.
