---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1069.003"
stix_relationship_id: "relationship--f453dbd9-d26e-4e56-88eb-25d37f7aae39"
---
# Relationship 9200: G1057 — uses → T1069.003

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.003 - Cloud Groups|T1069.003: Cloud Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has executed API calls to enumerate permissions for compromised AWS accounts.(Citation: Unit42KelleyVaya_BlingLibra_Aug2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f453dbd9-d26e-4e56-88eb-25d37f7aae39`.
