---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0435"
target_object: "T1010"
stix_relationship_id: "relationship--e98a5dc7-707a-4933-801a-b98b2e44b309"
---
# Relationship 5724: S0435 — uses → T1010

**Source object:** [[01 ATT&CK/S0435 - PLEAD|S0435: PLEAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PLEAD](https://attack.mitre.org/software/S0435) has the ability to list open windows on the compromised host.(Citation: TrendMicro BlackTech June 2017)(Citation: TrendMicro BlackTech June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e98a5dc7-707a-4933-801a-b98b2e44b309`.
