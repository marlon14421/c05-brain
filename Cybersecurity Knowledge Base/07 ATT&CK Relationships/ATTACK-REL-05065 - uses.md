---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0135"
target_object: "T1036.004"
stix_relationship_id: "relationship--f7fee577-ea37-4d2b-9353-8bfada984f55"
---
# Relationship 5065: G0135 — uses → T1036.004

**Source object:** [[01 ATT&CK/G0135 - BackdoorDiplomacy|G0135: BackdoorDiplomacy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BackdoorDiplomacy](https://attack.mitre.org/groups/G0135) has disguised their backdoor droppers with naming conventions designed to blend into normal operations.(Citation: ESET BackdoorDiplomacy Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7fee577-ea37-4d2b-9353-8bfada984f55`.
