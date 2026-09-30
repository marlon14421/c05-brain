---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0614"
target_object: "T1027.001"
stix_relationship_id: "relationship--8a8fa25a-8cc6-4bd1-a97a-a0d9df9c1507"
---
# Relationship 8693: S0614 — uses → T1027.001

**Source object:** [[01 ATT&CK/S0614 - CostaBricks|S0614: CostaBricks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.001 - Binary Padding|T1027.001: Binary Padding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CostaBricks](https://attack.mitre.org/software/S0614) has added the entire unobfuscated code of the legitimate open source application Blink to its code.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a8fa25a-8cc6-4bd1-a97a-a0d9df9c1507`.
