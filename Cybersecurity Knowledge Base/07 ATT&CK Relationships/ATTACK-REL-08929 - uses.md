---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0257"
target_object: "T1027.002"
stix_relationship_id: "relationship--141d1c0d-2f56-4b56-8834-ca3dab22faf9"
---
# Relationship 8929: S0257 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0257 - VERMIN|S0257: VERMIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VERMIN](https://attack.mitre.org/software/S0257) is initially packed.(Citation: Unit 42 VERMIN Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--141d1c0d-2f56-4b56-8834-ca3dab22faf9`.
