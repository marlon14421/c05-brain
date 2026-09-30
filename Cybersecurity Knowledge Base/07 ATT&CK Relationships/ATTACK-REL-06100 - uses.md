---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0105"
target_object: "T1069.002"
stix_relationship_id: "relationship--f36a8899-940f-4c8f-924d-eef2f056744d"
---
# Relationship 6100: S0105 — uses → T1069.002

**Source object:** [[01 ATT&CK/S0105 - dsquery|S0105: dsquery]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[dsquery](https://attack.mitre.org/software/S0105) can be used to gather information on permission groups within a domain.(Citation: TechNet Dsquery)(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f36a8899-940f-4c8f-924d-eef2f056744d`.
