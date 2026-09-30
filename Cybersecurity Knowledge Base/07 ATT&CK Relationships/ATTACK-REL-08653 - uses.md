---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0062"
target_object: "T1082"
stix_relationship_id: "relationship--c008b7f3-0507-4987-a7e4-8c4d57cb4ca5"
---
# Relationship 8653: S0062 — uses → T1082

**Source object:** [[01 ATT&CK/S0062 - DustySky|S0062: DustySky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DustySky](https://attack.mitre.org/software/S0062) extracts basic information about the operating system.(Citation: DustySky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c008b7f3-0507-4987-a7e4-8c4d57cb4ca5`.
