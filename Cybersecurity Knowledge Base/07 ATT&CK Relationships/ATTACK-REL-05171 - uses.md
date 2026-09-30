---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9044"
target_object: "T1059.007"
stix_relationship_id: "relationship--cfb02b3d-c902-480f-a579-06ac4ba0c5a4"
---
# Relationship 5171: S9044 — uses → T1059.007

**Source object:** [[01 ATT&CK/S9044 - Kali365|S9044: Kali365]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kali365](https://attack.mitre.org/software/S9044) has executed JavaScript within victims' browsers through a React frontend that detects browser sessions to evade automated analysis, auto-copies actor-generated device codes to the victim's clipboard, and polls the actor's C2 infrastructure every three seconds to confirm when OAuth token capture has completed..(Citation: Artic Wolf Labs Kali365 Device Code April 2026)(Citation: Artic Wolf Kali365 Device Code OAuth June 2026)(Citation: Huntress Kali365 Device Code June 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfb02b3d-c902-480f-a579-06ac4ba0c5a4`.
