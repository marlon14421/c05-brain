---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0023"
target_object: "T1012"
stix_relationship_id: "relationship--f55d54fe-27ed-41f9-81db-11ccbe2d2125"
---
# Relationship 7530: S0023 — uses → T1012

**Source object:** [[01 ATT&CK/S0023 - CHOPSTICK|S0023: CHOPSTICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHOPSTICK](https://attack.mitre.org/software/S0023) provides access to the Windows Registry, which can be used to gather information.(Citation: FireEye APT28)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f55d54fe-27ed-41f9-81db-11ccbe2d2125`.
