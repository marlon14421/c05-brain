---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1055.001"
stix_relationship_id: "relationship--4d0ea359-36b3-46f8-818a-5aaff3de574a"
---
# Relationship 6608: S0182 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) injects itself into various processes depending on whether it is low integrity or high integrity.(Citation: FinFisher Citation)(Citation: Microsoft FinFisher March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4d0ea359-36b3-46f8-818a-5aaff3de574a`.
