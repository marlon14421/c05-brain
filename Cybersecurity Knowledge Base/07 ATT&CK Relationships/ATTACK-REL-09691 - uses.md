---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0022"
target_object: "T1218.011"
stix_relationship_id: "relationship--555e47f2-54bb-4c97-8804-536aa354126c"
---
# Relationship 9691: G0022 — uses → T1218.011

**Source object:** [[01 ATT&CK/G0022 - APT3|G0022: APT3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT3](https://attack.mitre.org/groups/G0022) has a tool that can run DLLs.(Citation: FireEye Clandestine Fox)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--555e47f2-54bb-4c97-8804-536aa354126c`.
