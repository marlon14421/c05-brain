---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0149"
target_object: "T1120"
stix_relationship_id: "relationship--5cceffd9-5818-4481-bce6-4e326548d6b4"
---
# Relationship 7028: S0149 — uses → T1120

**Source object:** [[01 ATT&CK/S0149 - MoonWind|S0149: MoonWind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoonWind](https://attack.mitre.org/software/S0149) obtains the number of removable drives from the victim.(Citation: Palo Alto MoonWind March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cceffd9-5818-4481-bce6-4e326548d6b4`.
