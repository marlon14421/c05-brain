---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0504"
target_object: "T1105"
stix_relationship_id: "relationship--116996cd-b855-4730-814d-869fd90e7ce1"
---
# Relationship 9351: S0504 — uses → T1105

**Source object:** [[01 ATT&CK/S0504 - Anchor|S0504: Anchor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Anchor](https://attack.mitre.org/software/S0504) can download additional payloads.(Citation: Cyberreason Anchor December 2019)(Citation: Medium Anchor DNS July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--116996cd-b855-4730-814d-869fd90e7ce1`.
