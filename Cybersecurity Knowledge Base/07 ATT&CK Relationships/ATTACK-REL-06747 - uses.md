---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0373"
target_object: "T1082"
stix_relationship_id: "relationship--29d3798c-dc27-4950-abc4-30b48608a746"
---
# Relationship 6747: S0373 — uses → T1082

**Source object:** [[01 ATT&CK/S0373 - Astaroth|S0373: Astaroth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Astaroth](https://attack.mitre.org/software/S0373) collects the machine name and keyboard language from the system. (Citation: Cofense Astaroth Sept 2018)(Citation: Cybereason Astaroth Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29d3798c-dc27-4950-abc4-30b48608a746`.
