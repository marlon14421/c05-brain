---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1007"
target_object: "T1083"
stix_relationship_id: "relationship--767ce5fe-06f5-4efc-aa41-129fad867c65"
---
# Relationship 5616: G1007 — uses → T1083

**Source object:** [[01 ATT&CK/G1007 - Aoqin Dragon|G1007: Aoqin Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aoqin Dragon](https://attack.mitre.org/groups/G1007) has run scripts to identify file formats including Microsoft Word.(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--767ce5fe-06f5-4efc-aa41-129fad867c65`.
