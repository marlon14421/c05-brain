---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0662"
target_object: "T1547.001"
stix_relationship_id: "relationship--ab1d783b-d6b3-439c-a5f4-701a8cae4c6a"
---
# Relationship 5792: S0662 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0662 - RCSession|S0662: RCSession]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RCSession](https://attack.mitre.org/software/S0662) has the ability to modify a Registry Run key to establish persistence.(Citation: Trend Micro DRBControl February 2020)(Citation: Profero APT27 December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab1d783b-d6b3-439c-a5f4-701a8cae4c6a`.
