---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1003"
target_object: "S0488"
stix_relationship_id: "relationship--71b0e83e-8b1e-41ea-b7ec-35f66a3ee9d8"
---
# Relationship 7562: G1003 — uses → S0488

**Source object:** [[01 ATT&CK/G1003 - Ember Bear|G1003: Ember Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0488 - CrackMapExec|S0488: CrackMapExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ember Bear](https://attack.mitre.org/groups/G1003) used [CrackMapExec](https://attack.mitre.org/software/S0488) during intrusions.(Citation: CISA GRU29155 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71b0e83e-8b1e-41ea-b7ec-35f66a3ee9d8`.
