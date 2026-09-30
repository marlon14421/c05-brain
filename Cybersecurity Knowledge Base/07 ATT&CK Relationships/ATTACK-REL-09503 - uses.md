---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1053"
target_object: "T1027.007"
stix_relationship_id: "relationship--7b275e8a-83fd-4f2b-8ec4-eb36dae007fd"
---
# Relationship 9503: S1053 — uses → T1027.007

**Source object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.007 - Dynamic API Resolution|T1027.007: Dynamic API Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053) has used obfuscated API calls that are retrieved by their checksums.(Citation: Malwarebytes AvosLocker Jul 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b275e8a-83fd-4f2b-8ec4-eb36dae007fd`.
