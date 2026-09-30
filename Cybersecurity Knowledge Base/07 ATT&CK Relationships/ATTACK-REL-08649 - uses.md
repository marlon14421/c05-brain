---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0668"
target_object: "T1106"
stix_relationship_id: "relationship--1a471326-20d2-41e2-8dc5-dd9d9ce5a7e1"
---
# Relationship 8649: S0668 — uses → T1106

**Source object:** [[01 ATT&CK/S0668 - TinyTurla|S0668: TinyTurla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TinyTurla](https://attack.mitre.org/software/S0668) has used `WinHTTP`, `CreateProcess`, and other APIs for C2 communications and other functions.(Citation: Talos TinyTurla September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a471326-20d2-41e2-8dc5-dd9d9ce5a7e1`.
