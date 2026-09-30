---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0511"
target_object: "T1027"
stix_relationship_id: "relationship--c1b912a1-ffb4-4b33-88ec-6a567a1fcfd4"
---
# Relationship 9636: S0511 — uses → T1027

**Source object:** [[01 ATT&CK/S0511 - RegDuke|S0511: RegDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RegDuke](https://attack.mitre.org/software/S0511) can use control-flow flattening or the commercially available .NET Reactor for obfuscation.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1b912a1-ffb4-4b33-88ec-6a567a1fcfd4`.
