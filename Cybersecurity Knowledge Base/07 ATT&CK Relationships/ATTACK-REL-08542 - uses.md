---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1120"
target_object: "T1140"
stix_relationship_id: "relationship--eacb139c-69ea-44a5-b299-6a2db03e4079"
---
# Relationship 8542: S1120 — uses → T1140

**Source object:** [[01 ATT&CK/S1120 - FRAMESTING|S1120: FRAMESTING]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FRAMESTING](https://attack.mitre.org/software/S1120) can decompress data received within `POST` requests.(Citation: Mandiant Cutting Edge Part 2 January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eacb139c-69ea-44a5-b299-6a2db03e4079`.
