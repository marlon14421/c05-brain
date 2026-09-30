---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0565"
target_object: "T1027.002"
stix_relationship_id: "relationship--1c8951ff-5de9-4842-b889-0c439aa76e8f"
---
# Relationship 7031: S0565 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0565 - Raindrop|S0565: Raindrop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raindrop](https://attack.mitre.org/software/S0565) used a custom packer for its [Cobalt Strike](https://attack.mitre.org/software/S0154) payload, which was compressed using the LZMA algorithm.(Citation: Symantec RAINDROP January 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c8951ff-5de9-4842-b889-0c439aa76e8f`.
