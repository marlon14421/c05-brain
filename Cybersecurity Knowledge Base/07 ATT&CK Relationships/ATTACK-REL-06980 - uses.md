---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0107"
target_object: "T1027.013"
stix_relationship_id: "relationship--95c6eafc-4b3f-404b-86d9-13b4ae4845da"
---
# Relationship 6980: G0107 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0107 - Whitefly|G0107: Whitefly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Whitefly](https://attack.mitre.org/groups/G0107) has encrypted the payload used for C2.(Citation: Symantec Whitefly March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95c6eafc-4b3f-404b-86d9-13b4ae4845da`.
