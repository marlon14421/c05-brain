---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0670"
target_object: "T1564.003"
stix_relationship_id: "relationship--b0bac30d-7e77-41dd-9af8-c3daab9fa7b8"
---
# Relationship 7174: S0670 — uses → T1564.003

**Source object:** [[01 ATT&CK/S0670 - WarzoneRAT|S0670: WarzoneRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

WarzoneRAT has the ability of performing remote desktop access via a hVNC window for decreased visibility.(Citation: Bitdefender Trickbot VNC module Whitepaper 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0bac30d-7e77-41dd-9af8-c3daab9fa7b8`.
