---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1124"
stix_relationship_id: "relationship--08d7395b-b3e6-4ae2-be46-31347d1d5eaa"
---
# Relationship 7226: S0011 — uses → T1124

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) can use GetLocalTime and GetSystemTime to collect system time.(Citation: CISA MAR-10292089-1.v2 TAIDOOR August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08d7395b-b3e6-4ae2-be46-31347d1d5eaa`.
