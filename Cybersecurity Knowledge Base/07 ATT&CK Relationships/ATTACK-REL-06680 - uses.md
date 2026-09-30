---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1141"
target_object: "T1135"
stix_relationship_id: "relationship--3bb1eae7-1653-4a38-9b4b-6bd93503f6ca"
---
# Relationship 6680: S1141 — uses → T1135

**Source object:** [[01 ATT&CK/S1141 - LunarWeb|S1141: LunarWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarWeb](https://attack.mitre.org/software/S1141) can identify shared resources in compromised environments.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3bb1eae7-1653-4a38-9b4b-6bd93503f6ca`.
