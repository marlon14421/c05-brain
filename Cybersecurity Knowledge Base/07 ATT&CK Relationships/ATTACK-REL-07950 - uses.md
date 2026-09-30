---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0339"
target_object: "T1113"
stix_relationship_id: "relationship--b8a7be73-89a5-4689-8eea-280b745bd3cc"
---
# Relationship 7950: S0339 — uses → T1113

**Source object:** [[01 ATT&CK/S0339 - Micropsia|S0339: Micropsia]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Micropsia](https://attack.mitre.org/software/S0339) takes screenshots every 90 seconds by calling the Gdi32.BitBlt API.(Citation: Radware Micropsia July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b8a7be73-89a5-4689-8eea-280b745bd3cc`.
