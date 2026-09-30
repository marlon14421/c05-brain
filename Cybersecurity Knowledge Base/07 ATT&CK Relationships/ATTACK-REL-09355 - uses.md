---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0661"
target_object: "T1560.002"
stix_relationship_id: "relationship--990e64f6-6a47-410c-9557-a17e96a60755"
---
# Relationship 9355: S0661 — uses → T1560.002

**Source object:** [[01 ATT&CK/S0661 - FoggyWeb|S0661: FoggyWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.002 - Archive via Library|T1560.002: Archive via Library]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FoggyWeb](https://attack.mitre.org/software/S0661) can invoke the `Common.Compress` method to compress data with the C# GZipStream compression class.(Citation: MSTIC FoggyWeb September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--990e64f6-6a47-410c-9557-a17e96a60755`.
