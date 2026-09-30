---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0458"
target_object: "T1560.001"
stix_relationship_id: "relationship--756f3884-c21b-4d00-ac2c-6c2ab386072f"
---
# Relationship 6823: S0458 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0458 - Ramsay|S0458: Ramsay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) can compress and archive collected files using WinRAR.(Citation: Eset Ramsay May 2020)(Citation: Antiy CERT Ramsay April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--756f3884-c21b-4d00-ac2c-6c2ab386072f`.
