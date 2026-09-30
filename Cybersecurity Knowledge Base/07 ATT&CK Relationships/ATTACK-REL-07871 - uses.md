---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1683.002"
stix_relationship_id: "relationship--fc6b549d-3f8a-447f-bc6f-a8133334dc15"
---
# Relationship 7871: G1052 — uses → T1683.002

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1683.002 - Audio-Visual Content|T1683.002: Audio-Visual Content]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has used AI to clone video-conferencing applications to distribute their [BeaverTail](https://attack.mitre.org/software/S1246) malware. They have also used AI to create deepfake videos. (Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc6b549d-3f8a-447f-bc6f-a8133334dc15`.
