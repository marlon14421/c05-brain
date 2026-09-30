---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1547.001"
stix_relationship_id: "relationship--e7f60c3a-5b9e-4175-8bac-72773f580dad"
---
# Relationship 8444: S0428 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) has added a registry key in the hive for persistence.(Citation: Talos PoetRAT April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7f60c3a-5b9e-4175-8bac-72773f580dad`.
