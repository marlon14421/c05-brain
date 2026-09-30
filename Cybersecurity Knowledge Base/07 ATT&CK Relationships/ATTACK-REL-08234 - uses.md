---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0192"
target_object: "T1055.001"
stix_relationship_id: "relationship--4a0cbe7f-e88c-4ef6-8bf7-9f6e17e8de04"
---
# Relationship 8234: S0192 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pupy](https://attack.mitre.org/software/S0192) can migrate into another process using reflective DLL injection.(Citation: GitHub Pupy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a0cbe7f-e88c-4ef6-8bf7-9f6e17e8de04`.
