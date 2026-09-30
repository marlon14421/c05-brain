---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0640"
target_object: "T1027"
stix_relationship_id: "relationship--cc134d2d-64eb-469a-b8eb-90ea632c0adc"
---
# Relationship 8228: S0640 — uses → T1027

**Source object:** [[01 ATT&CK/S0640 - Avaddon|S0640: Avaddon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Avaddon](https://attack.mitre.org/software/S0640) has used encrypted strings.(Citation: Arxiv Avaddon Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc134d2d-64eb-469a-b8eb-90ea632c0adc`.
