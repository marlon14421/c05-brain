---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0113"
target_object: "T1547.001"
stix_relationship_id: "relationship--c5fa4766-4468-4afd-9b5f-5ce4f443729d"
---
# Relationship 5799: S0113 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0113 - Prikormka|S0113: Prikormka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Prikormka](https://attack.mitre.org/software/S0113) adds itself to a Registry Run key with the name guidVGA or guidVSA.(Citation: ESET Operation Groundbait)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5fa4766-4468-4afd-9b5f-5ce4f443729d`.
