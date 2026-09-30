---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "S0349"
stix_relationship_id: "relationship--64205021-48f8-4dbb-a731-e9c921bbf7f1"
---
# Relationship 7035: G1015 — uses → S0349

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) can obtain credential information using [LaZagne](https://attack.mitre.org/software/S0349).(Citation: MSTIC Octo Tempest Operations October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--64205021-48f8-4dbb-a731-e9c921bbf7f1`.
