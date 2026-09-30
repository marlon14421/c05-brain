---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0254"
target_object: "T1105"
stix_relationship_id: "relationship--fdea1dc1-4b00-411e-a5d3-cd72688237b5"
---
# Relationship 5783: S0254 — uses → T1105

**Source object:** [[01 ATT&CK/S0254 - PLAINTEE|S0254: PLAINTEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PLAINTEE](https://attack.mitre.org/software/S0254) has downloaded and executed additional plugins.(Citation: Rancor Unit42 June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdea1dc1-4b00-411e-a5d3-cd72688237b5`.
