---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0044"
target_object: "T1014"
stix_relationship_id: "relationship--05e05236-1635-48d7-8ee3-33319c01c815"
---
# Relationship 9551: G0044 — uses → T1014

**Source object:** [[01 ATT&CK/G0044 - Winnti Group|G0044: Winnti Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winnti Group](https://attack.mitre.org/groups/G0044) used a rootkit to modify typical server functionality.(Citation: Kaspersky Winnti April 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05e05236-1635-48d7-8ee3-33319c01c815`.
