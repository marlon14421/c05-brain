---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1102.002"
stix_relationship_id: "relationship--3f37a188-b994-4191-aee1-56d0c60101e1"
---
# Relationship 5222: S0128 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADNEWS](https://attack.mitre.org/software/S0128) can use multiple C2 channels, including RSS feeds, Github, forums, and blogs.(Citation: Forcepoint Monsoon)(Citation: PaloAlto Patchwork Mar 2018)(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f37a188-b994-4191-aee1-56d0c60101e1`.
