---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0267"
target_object: "T1124"
stix_relationship_id: "relationship--8b6dbaf7-d578-4bc6-8f16-07e7c1aeedc8"
---
# Relationship 7426: S0267 — uses → T1124

**Source object:** [[01 ATT&CK/S0267 - FELIXROOT|S0267: FELIXROOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FELIXROOT](https://attack.mitre.org/software/S0267) gathers the time zone information from the victim’s machine.(Citation: ESET GreyEnergy Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b6dbaf7-d578-4bc6-8f16-07e7c1aeedc8`.
