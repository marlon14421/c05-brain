---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0575"
target_object: "T1490"
stix_relationship_id: "relationship--9e22871c-2e16-4c81-903c-e081c140f7a2"
---
# Relationship 9474: S0575 — uses → T1490

**Source object:** [[01 ATT&CK/S0575 - Conti|S0575: Conti]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conti](https://attack.mitre.org/software/S0575) can delete Windows Volume Shadow Copies using vssadmin .(Citation: CarbonBlack Conti July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e22871c-2e16-4c81-903c-e081c140f7a2`.
