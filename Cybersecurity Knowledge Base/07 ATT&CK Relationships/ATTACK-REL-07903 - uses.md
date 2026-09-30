---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0498"
target_object: "T1033"
stix_relationship_id: "relationship--e3fe5089-90fc-47e6-afc7-fb0c41ba7c0c"
---
# Relationship 7903: S0498 — uses → T1033

**Source object:** [[01 ATT&CK/S0498 - Cryptoistic|S0498: Cryptoistic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cryptoistic](https://attack.mitre.org/software/S0498) can gather data on the user of a compromised host.(Citation: SentinelOne Lazarus macOS July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3fe5089-90fc-47e6-afc7-fb0c41ba7c0c`.
