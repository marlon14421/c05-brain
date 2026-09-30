---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1162"
target_object: "T1490"
stix_relationship_id: "relationship--26fe80fc-b6ec-4ca0-8693-d61e63901af3"
---
# Relationship 7902: S1162 — uses → T1490

**Source object:** [[01 ATT&CK/S1162 - Playcrypt|S1162: Playcrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Playcrypt](https://attack.mitre.org/software/S1162) can use AlphaVSS to delete shadow copies.(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26fe80fc-b6ec-4ca0-8693-d61e63901af3`.
