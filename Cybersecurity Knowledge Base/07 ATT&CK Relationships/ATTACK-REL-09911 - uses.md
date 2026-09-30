---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0553"
target_object: "T1105"
stix_relationship_id: "relationship--cca578fe-fe2d-44ef-bc55-9518f83f1443"
---
# Relationship 9911: S0553 — uses → T1105

**Source object:** [[01 ATT&CK/S0553 - MoleNet|S0553: MoleNet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoleNet](https://attack.mitre.org/software/S0553) can download additional payloads from the C2.(Citation: Cybereason Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cca578fe-fe2d-44ef-bc55-9518f83f1443`.
