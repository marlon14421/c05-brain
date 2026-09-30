---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0123"
target_object: "T1595.002"
stix_relationship_id: "relationship--1637c874-852e-4ab9-b6e0-2c855da74ef0"
---
# Relationship 6082: G0123 — uses → T1595.002

**Source object:** [[01 ATT&CK/G0123 - Volatile Cedar|G0123: Volatile Cedar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1595.002 - Vulnerability Scanning|T1595.002: Vulnerability Scanning]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volatile Cedar](https://attack.mitre.org/groups/G0123) has performed vulnerability scans of the target server.(Citation: CheckPoint Volatile Cedar March 2015)(Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1637c874-852e-4ab9-b6e0-2c855da74ef0`.
