---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0564"
target_object: "T1071.001"
stix_relationship_id: "relationship--2d72a376-5bfb-4e6b-a79f-2f75f97de99e"
---
# Relationship 9274: S0564 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0564 - BlackMould|S0564: BlackMould]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackMould](https://attack.mitre.org/software/S0564) can send commands to C2 in the body of HTTP POST requests.(Citation: Microsoft GALLIUM December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d72a376-5bfb-4e6b-a79f-2f75f97de99e`.
