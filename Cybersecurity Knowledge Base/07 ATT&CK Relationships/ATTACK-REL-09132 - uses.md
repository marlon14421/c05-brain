---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0044"
target_object: "T1070.004"
stix_relationship_id: "relationship--edaa004e-8239-40d8-a4f0-8849c4f0e87f"
---
# Relationship 9132: S0044 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0044 - JHUHUGIT|S0044: JHUHUGIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [JHUHUGIT](https://attack.mitre.org/software/S0044) dropper can delete itself from the victim. Another [JHUHUGIT](https://attack.mitre.org/software/S0044) variant has the capability to delete specified files.(Citation: ESET Sednit Part 1)(Citation: Unit 42 Sofacy Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edaa004e-8239-40d8-a4f0-8849c4f0e87f`.
