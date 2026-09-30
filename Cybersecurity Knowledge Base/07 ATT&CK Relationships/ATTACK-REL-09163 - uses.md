---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0004"
target_object: "S0615"
stix_relationship_id: "relationship--699be82f-c548-4e2b-a33c-f91ceed1bf9f"
---
# Relationship 9163: C0004 — uses → S0615

**Source object:** [[01 ATT&CK/C0004 - CostaRicto|C0004: CostaRicto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [CostaRicto](https://attack.mitre.org/campaigns/C0004), threat actors used [SombRAT](https://attack.mitre.org/software/S0615) in conjuction with [CostaBricks](https://attack.mitre.org/software/S0614) and [PowerSploit](https://attack.mitre.org/software/S0194).(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--699be82f-c548-4e2b-a33c-f91ceed1bf9f`.
