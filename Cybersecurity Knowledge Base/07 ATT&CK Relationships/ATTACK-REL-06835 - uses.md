---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1583.001"
stix_relationship_id: "relationship--72ebbe49-a354-4894-bfa2-06016f3d1ae6"
---
# Relationship 6835: S1130 — uses → T1583.001

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) uses newly-registered domains containing only a few characters for command and controll purposes, such as " v0[.]cx ".(Citation: RedCanary RaspberryRobin 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72ebbe49-a354-4894-bfa2-06016f3d1ae6`.
