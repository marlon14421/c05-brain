---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0520"
target_object: "T1059.003"
stix_relationship_id: "relationship--170fb051-0d3d-4105-b6d2-96c9c68e4b8c"
---
# Relationship 5517: S0520 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0520 - BLINDINGCAN|S0520: BLINDINGCAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLINDINGCAN](https://attack.mitre.org/software/S0520) has executed commands via cmd.exe.(Citation: US-CERT BLINDINGCAN Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--170fb051-0d3d-4105-b6d2-96c9c68e4b8c`.
