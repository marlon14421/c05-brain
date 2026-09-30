---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1145"
target_object: "T1622"
stix_relationship_id: "relationship--44a27941-a92a-4dd8-ab62-e30f6d8782e3"
---
# Relationship 5510: S1145 — uses → T1622

**Source object:** [[01 ATT&CK/S1145 - Pikabot|S1145: Pikabot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) features several methods to evade debugging by analysts, including checks for active debuggers, the use of breakpoints during execution, and checking various system information items such as system memory and the number of processors.(Citation: Zscaler Pikabot 2023)(Citation: Elastic Pikabot 2024)(Citation: Logpoint Pikabot 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44a27941-a92a-4dd8-ab62-e30f6d8782e3`.
