---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1003"
target_object: "S1018"
stix_relationship_id: "relationship--ab225de5-cdbc-4026-87ee-f64d3c22336d"
---
# Relationship 7923: G1003 — uses → S1018

**Source object:** [[01 ATT&CK/G1003 - Ember Bear|G1003: Ember Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1018 - Saint Bot|S1018: Saint Bot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ember Bear](https://attack.mitre.org/groups/G1003) has used [Saint Bot](https://attack.mitre.org/software/S1018) during operations, but is distinct from the threat actor [Saint Bear](https://attack.mitre.org/groups/G1031).(Citation: CISA GRU29155 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab225de5-cdbc-4026-87ee-f64d3c22336d`.
