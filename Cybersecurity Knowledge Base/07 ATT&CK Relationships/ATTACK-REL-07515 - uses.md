---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0070"
target_object: "T1027.002"
stix_relationship_id: "relationship--31fb3ebe-3fc9-4257-b7d5-a1b12b54bbe3"
---
# Relationship 7515: G0070 — uses → T1027.002

**Source object:** [[01 ATT&CK/G0070 - Dark Caracal|G0070: Dark Caracal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dark Caracal](https://attack.mitre.org/groups/G0070) has used UPX to pack [Bandook](https://attack.mitre.org/software/S0234).(Citation: Lookout Dark Caracal Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31fb3ebe-3fc9-4257-b7d5-a1b12b54bbe3`.
