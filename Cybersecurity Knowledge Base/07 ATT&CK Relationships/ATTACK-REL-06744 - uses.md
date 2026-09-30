---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0144"
target_object: "T1547.001"
stix_relationship_id: "relationship--2e44b66a-0f81-4f60-94aa-c450556bc243"
---
# Relationship 6744: S0144 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0144 - ChChes|S0144: ChChes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ChChes](https://attack.mitre.org/software/S0144) establishes persistence by adding a Registry Run key.(Citation: PWC Cloud Hopper Technical Annex April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e44b66a-0f81-4f60-94aa-c450556bc243`.
