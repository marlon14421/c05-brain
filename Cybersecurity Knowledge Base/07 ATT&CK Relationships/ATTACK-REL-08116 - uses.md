---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1023"
target_object: "T1136.001"
stix_relationship_id: "relationship--0782e7d8-3df6-4eb4-99a9-3d3a74c7752c"
---
# Relationship 8116: G1023 — uses → T1136.001

**Source object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT5](https://attack.mitre.org/groups/G1023) has created Local Administrator accounts to maintain access to systems with short-cycle credential rotation.(Citation: Mandiant Pulse Secure Update May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0782e7d8-3df6-4eb4-99a9-3d3a74c7752c`.
