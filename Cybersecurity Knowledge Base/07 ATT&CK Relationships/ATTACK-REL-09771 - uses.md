---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1105"
stix_relationship_id: "relationship--b3f53743-4bd9-47a6-bf41-6f7786bbdc87"
---
# Relationship 9771: S0128 — uses → T1105

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADNEWS](https://attack.mitre.org/software/S0128) is capable of downloading additional files through C2 channels, including a new version of itself.(Citation: Forcepoint Monsoon)(Citation: PaloAlto Patchwork Mar 2018)(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3f53743-4bd9-47a6-bf41-6f7786bbdc87`.
