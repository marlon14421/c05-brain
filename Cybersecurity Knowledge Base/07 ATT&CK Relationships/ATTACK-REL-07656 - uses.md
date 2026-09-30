---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0612"
target_object: "T1059.003"
stix_relationship_id: "relationship--739b4be2-ad4d-4a40-997f-958292c860a1"
---
# Relationship 7656: S0612 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0612 - WastedLocker|S0612: WastedLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WastedLocker](https://attack.mitre.org/software/S0612) has used [cmd](https://attack.mitre.org/software/S0106) to execute commands on the system.(Citation: NCC Group WastedLocker June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--739b4be2-ad4d-4a40-997f-958292c860a1`.
