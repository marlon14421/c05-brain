---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1178"
target_object: "T1059.005"
stix_relationship_id: "relationship--41681a87-79e2-4daf-bc5f-cdfea1b47a50"
---
# Relationship 9685: S1178 — uses → T1059.005

**Source object:** [[01 ATT&CK/S1178 - ShrinkLocker|S1178: ShrinkLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShrinkLocker](https://attack.mitre.org/software/S1178) is a VisualBasic script (VBS) object that calls multiple other operating system functions during execution.(Citation: Kaspersky ShrinkLocker 2024)(Citation: Splunk ShrinkLocker 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41681a87-79e2-4daf-bc5f-cdfea1b47a50`.
