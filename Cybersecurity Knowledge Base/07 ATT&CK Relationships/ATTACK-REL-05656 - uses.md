---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1047"
stix_relationship_id: "relationship--9e80392b-1b7c-4e82-9fbf-73d8ddb6b876"
---
# Relationship 5656: S0496 — uses → T1047

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REvil](https://attack.mitre.org/software/S0496) can use WMI to monitor for and kill specific processes listed in its configuration file.(Citation: Secureworks GandCrab and REvil September 2019)(Citation: Group IB Ransomware May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e80392b-1b7c-4e82-9fbf-73d8ddb6b876`.
