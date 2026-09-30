---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1102"
stix_relationship_id: "relationship--1b40e3b0-a862-4c79-a8e6-a008e71f6028"
---
# Relationship 8627: S1086 — uses → T1102

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) can download additional payloads from web services including Pastebin and top4top.(Citation: Morphisec Snip3 May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b40e3b0-a862-4c79-a8e6-a008e71f6028`.
