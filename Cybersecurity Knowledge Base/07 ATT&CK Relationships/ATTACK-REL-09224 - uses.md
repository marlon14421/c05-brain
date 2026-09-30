---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "S9021"
stix_relationship_id: "relationship--ad586838-f312-4956-94e4-2c80b653430f"
---
# Relationship 9224: G1054 — uses → S9021

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) has been used by [MirrorFace](https://attack.mitre.org/groups/G1054) to download [LODEINFO](https://attack.mitre.org/software/S9020).(Citation: Kaspersky LODEINFO OCT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad586838-f312-4956-94e4-2c80b653430f`.
