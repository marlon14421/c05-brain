---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1564.004"
stix_relationship_id: "relationship--1eeb08cb-8b06-45a7-bf74-fb8bdaa4b02f"
---
# Relationship 9475: G0050 — uses → T1564.004

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.004 - NTFS File Attributes|T1564.004: NTFS File Attributes]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) used NTFS alternate data streams to hide their payloads.(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1eeb08cb-8b06-45a7-bf74-fb8bdaa4b02f`.
