---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1172"
target_object: "T1564.003"
stix_relationship_id: "relationship--62a9e155-9ecd-4781-8914-1c0e5183b98f"
---
# Relationship 6396: S1172 — uses → T1564.003

**Source object:** [[01 ATT&CK/S1172 - OilBooster|S1172: OilBooster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilBooster](https://attack.mitre.org/software/S1172) can hide its console window upon execution through the `ShowWindow` API. (Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62a9e155-9ecd-4781-8914-1c0e5183b98f`.
