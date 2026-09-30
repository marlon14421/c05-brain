---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1187"
target_object: "T1059.006"
stix_relationship_id: "relationship--2b918315-a5bb-4de7-b982-16d96979d428"
---
# Relationship 8766: S1187 — uses → T1059.006

**Source object:** [[01 ATT&CK/S1187 - reGeorg|S1187: reGeorg]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[reGeorg](https://attack.mitre.org/software/S1187) is a Python-based web shell.(Citation: GitHub reGeorg 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b918315-a5bb-4de7-b982-16d96979d428`.
