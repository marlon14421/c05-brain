---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0048"
target_object: "S1164"
stix_relationship_id: "relationship--467d6065-8f8f-46f2-917d-cdd9a9da5e91"
---
# Relationship 9023: C0048 — uses → S1164

**Source object:** [[01 ATT&CK/C0048 - Operation MidnightEclipse|C0048: Operation MidnightEclipse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation MidnightEclipse](https://attack.mitre.org/campaigns/C0048), threat actors made multiple attempts to install [UPSTYLE](https://attack.mitre.org/software/S1164)(Citation: Volexity UPSTYLE 2024)(Citation: Palo Alto MidnightEclipse APR 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--467d6065-8f8f-46f2-917d-cdd9a9da5e91`.
