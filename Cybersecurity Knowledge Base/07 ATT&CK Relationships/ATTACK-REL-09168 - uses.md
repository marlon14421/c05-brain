---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0447"
target_object: "T1053"
stix_relationship_id: "relationship--85b5efa3-9bd0-4685-a211-78f17a3747c7"
---
# Relationship 9168: S0447 — uses → T1053

**Source object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053 - Scheduled Task-Job|T1053: Scheduled Task/Job]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lokibot](https://attack.mitre.org/software/S0447)'s second stage DLL has set a timer using “timeSetEvent” to schedule its next execution.(Citation: Talos Lokibot Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85b5efa3-9bd0-4685-a211-78f17a3747c7`.
