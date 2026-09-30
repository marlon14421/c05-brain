---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0500"
target_object: "T1053.005"
stix_relationship_id: "relationship--bb16d8ce-3017-4835-a282-b11d10abc8a1"
---
# Relationship 8767: S0500 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0500 - MCMD|S0500: MCMD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MCMD](https://attack.mitre.org/software/S0500) can use scheduled tasks for persistence.(Citation: Secureworks MCMD July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb16d8ce-3017-4835-a282-b11d10abc8a1`.
