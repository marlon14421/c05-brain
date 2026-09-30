---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0262"
target_object: "T1053.005"
stix_relationship_id: "relationship--f120a700-dcac-4c8d-8e92-d6ba3491c2ba"
---
# Relationship 10000: S0262 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QuasarRAT](https://attack.mitre.org/software/S0262) contains a .NET wrapper DLL for creating and managing scheduled tasks for maintaining persistence upon reboot.(Citation: Volexity Patchwork June 2018)(Citation: CISA AR18-352A Quasar RAT December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f120a700-dcac-4c8d-8e92-d6ba3491c2ba`.
