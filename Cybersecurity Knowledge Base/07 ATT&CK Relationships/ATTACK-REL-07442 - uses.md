---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0087"
target_object: "T1021.004"
stix_relationship_id: "relationship--fe8bc44b-805d-440c-a447-96091033439d"
---
# Relationship 7442: G0087 — uses → T1021.004

**Source object:** [[01 ATT&CK/G0087 - APT39|G0087: APT39]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.004 - SSH|T1021.004: SSH]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT39](https://attack.mitre.org/groups/G0087) used secure shell (SSH) to move laterally among their targets.(Citation: FireEye APT39 Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe8bc44b-805d-440c-a447-96091033439d`.
