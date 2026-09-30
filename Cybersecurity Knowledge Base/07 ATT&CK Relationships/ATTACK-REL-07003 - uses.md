---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "T1003.001"
stix_relationship_id: "relationship--9d82c2c5-7d98-40dd-9171-1d605f259064"
---
# Relationship 7003: G1006 — uses → T1003.001

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Earth Lusca](https://attack.mitre.org/groups/G1006) has used ProcDump to obtain the hashes of credentials by dumping the memory of the LSASS process.(Citation: TrendMicro EarthLusca 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d82c2c5-7d98-40dd-9171-1d605f259064`.
