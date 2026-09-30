---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "T1018"
stix_relationship_id: "relationship--95805281-96b1-49ea-95ee-9d654178c5c3"
---
# Relationship 5869: G0060 — uses → T1018

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRONZE BUTLER](https://attack.mitre.org/groups/G0060) typically use ping and [Net](https://attack.mitre.org/software/S0039) to enumerate systems.(Citation: Secureworks BRONZE BUTLER Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95805281-96b1-49ea-95ee-9d654178c5c3`.
