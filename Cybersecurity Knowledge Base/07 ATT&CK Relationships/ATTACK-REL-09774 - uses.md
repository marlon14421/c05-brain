---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0370"
target_object: "T1059.003"
stix_relationship_id: "relationship--341025e9-e0b8-4e9b-873c-40d7bc86e131"
---
# Relationship 9774: S0370 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0370 - SamSam|S0370: SamSam]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SamSam](https://attack.mitre.org/software/S0370) uses custom batch scripts to execute some of its components.(Citation: Sophos SamSam Apr 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--341025e9-e0b8-4e9b-873c-40d7bc86e131`.
