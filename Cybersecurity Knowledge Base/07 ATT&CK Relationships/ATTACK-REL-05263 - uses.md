---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0472"
target_object: "T1105"
stix_relationship_id: "relationship--0efece7a-dc3a-46e1-b56c-7db9e3b61149"
---
# Relationship 5263: S0472 — uses → T1105

**Source object:** [[01 ATT&CK/S0472 - down_new|S0472: down_new]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[down_new](https://attack.mitre.org/software/S0472) has the ability to download files to the compromised host.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0efece7a-dc3a-46e1-b56c-7db9e3b61149`.
