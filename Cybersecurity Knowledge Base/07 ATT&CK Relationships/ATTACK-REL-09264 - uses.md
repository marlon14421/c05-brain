---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1027.002"
stix_relationship_id: "relationship--347b7512-1e76-456f-9f04-0179d056ca9a"
---
# Relationship 9264: S0356 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) has been packed for obfuscation.(Citation: Malwarebytes KONNI Evolves Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--347b7512-1e76-456f-9f04-0179d056ca9a`.
