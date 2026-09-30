---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0512"
target_object: "T1059.001"
stix_relationship_id: "relationship--cbb5c722-bc07-4f35-a8cd-d6e1acc839d5"
---
# Relationship 8260: S0512 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0512 - FatDuke|S0512: FatDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FatDuke](https://attack.mitre.org/software/S0512) has the ability to execute PowerShell scripts.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbb5c722-bc07-4f35-a8cd-d6e1acc839d5`.
