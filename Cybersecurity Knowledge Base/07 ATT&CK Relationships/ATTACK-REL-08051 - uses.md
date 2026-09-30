---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0143"
target_object: "T1003.001"
stix_relationship_id: "relationship--c417561d-d3fa-4aa7-b272-6769b2ada225"
---
# Relationship 8051: G0143 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0143 - Aquatic Panda|G0143: Aquatic Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) has attempted to harvest credentials through LSASS memory dumping.(Citation: CrowdStrike AQUATIC PANDA December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c417561d-d3fa-4aa7-b272-6769b2ada225`.
