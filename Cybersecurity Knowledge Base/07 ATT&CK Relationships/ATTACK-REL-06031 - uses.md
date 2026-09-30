---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0283"
target_object: "T1125"
stix_relationship_id: "relationship--2043a8a7-d365-4f5c-9ee3-5b9be710f14d"
---
# Relationship 6031: S0283 — uses → T1125

**Source object:** [[01 ATT&CK/S0283 - jRAT|S0283: jRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[jRAT](https://attack.mitre.org/software/S0283) has the capability to capture video from a webcam.(Citation: jRAT Symantec Aug 2018)(Citation: Kaspersky Adwind Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2043a8a7-d365-4f5c-9ee3-5b9be710f14d`.
