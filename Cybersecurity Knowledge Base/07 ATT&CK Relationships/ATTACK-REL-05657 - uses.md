---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1112"
stix_relationship_id: "relationship--0775a1ba-c95a-472e-ab1c-d21108acc907"
---
# Relationship 5657: S0457 — uses → T1112

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Netwalker](https://attack.mitre.org/software/S0457) can add the following registry entry: HKEY_CURRENT_USER\SOFTWARE\{8 random characters} .(Citation: TrendMicro Netwalker May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0775a1ba-c95a-472e-ab1c-d21108acc907`.
