---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0342"
target_object: "T1105"
stix_relationship_id: "relationship--a21e7dd8-9194-4c09-870c-11f44f391838"
---
# Relationship 6329: S0342 — uses → T1105

**Source object:** [[01 ATT&CK/S0342 - GreyEnergy|S0342: GreyEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GreyEnergy](https://attack.mitre.org/software/S0342) can download additional modules and payloads.(Citation: ESET GreyEnergy Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a21e7dd8-9194-4c09-870c-11f44f391838`.
