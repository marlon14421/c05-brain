---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1001"
stix_relationship_id: "relationship--0e2c026d-042b-4ccb-b2d1-8ca6308ea506"
---
# Relationship 6918: G0047 — uses → T1001

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has used obfuscated VBScripts with randomly generated variable names and concatenated strings.(Citation: unit42_gamaredon_dec2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e2c026d-042b-4ccb-b2d1-8ca6308ea506`.
