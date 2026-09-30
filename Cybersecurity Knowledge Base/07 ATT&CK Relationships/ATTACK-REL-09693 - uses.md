---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0690"
target_object: "T1124"
stix_relationship_id: "relationship--e2250609-d3e3-4297-8564-aff8516f8dc3"
---
# Relationship 9693: S0690 — uses → T1124

**Source object:** [[01 ATT&CK/S0690 - Green Lambert|S0690: Green Lambert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Green Lambert](https://attack.mitre.org/software/S0690) can collect the date and time from a compromised host.(Citation: Objective See Green Lambert for OSX Oct 2021)(Citation: Glitch-Cat Green Lambert ATTCK Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2250609-d3e3-4297-8564-aff8516f8dc3`.
