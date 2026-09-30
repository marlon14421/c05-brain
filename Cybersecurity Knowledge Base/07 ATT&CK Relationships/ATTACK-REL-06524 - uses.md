---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0001"
target_object: "T1583.003"
stix_relationship_id: "relationship--a12a296d-3cdb-4a49-840a-4ecd073b5312"
---
# Relationship 6524: G0001 — uses → T1583.003

**Source object:** [[01 ATT&CK/G0001 - Axiom|G0001: Axiom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.003 - Virtual Private Server|T1583.003: Virtual Private Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Axiom](https://attack.mitre.org/groups/G0001) has used VPS hosting providers in targeting of intended victims.(Citation: Novetta-Axiom)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a12a296d-3cdb-4a49-840a-4ecd073b5312`.
