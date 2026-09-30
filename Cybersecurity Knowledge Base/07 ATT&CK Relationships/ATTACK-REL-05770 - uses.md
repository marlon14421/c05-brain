---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0450"
target_object: "T1082"
stix_relationship_id: "relationship--de70abfa-848f-4993-bdb8-7235d4a3d720"
---
# Relationship 5770: S0450 — uses → T1082

**Source object:** [[01 ATT&CK/S0450 - SHARPSTATS|S0450: SHARPSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SHARPSTATS](https://attack.mitre.org/software/S0450) has the ability to identify the IP address, machine name, and OS of the compromised host.(Citation: TrendMicro POWERSTATS V3 June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de70abfa-848f-4993-bdb8-7235d4a3d720`.
