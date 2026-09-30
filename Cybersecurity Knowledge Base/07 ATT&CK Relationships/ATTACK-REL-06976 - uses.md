---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0149"
target_object: "T1124"
stix_relationship_id: "relationship--77c63e89-71fe-47e3-babb-13e7722932ad"
---
# Relationship 6976: S0149 — uses → T1124

**Source object:** [[01 ATT&CK/S0149 - MoonWind|S0149: MoonWind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoonWind](https://attack.mitre.org/software/S0149) obtains the victim's current time.(Citation: Palo Alto MoonWind March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77c63e89-71fe-47e3-babb-13e7722932ad`.
