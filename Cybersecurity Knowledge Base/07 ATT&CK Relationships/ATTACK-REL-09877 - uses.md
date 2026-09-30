---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1105"
stix_relationship_id: "relationship--665f8af6-bdac-4574-9d8c-9c7829e0e4e7"
---
# Relationship 9877: S0011 — uses → T1105

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) has downloaded additional files onto a compromised host.(Citation: TrendMicro Taidoor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--665f8af6-bdac-4574-9d8c-9c7829e0e4e7`.
