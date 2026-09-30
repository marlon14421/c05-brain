---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0461"
target_object: "T1055.001"
stix_relationship_id: "relationship--27ccf817-33de-4d85-85e5-851f82e835e4"
---
# Relationship 5910: S0461 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0461 - SDBbot|S0461: SDBbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SDBbot](https://attack.mitre.org/software/S0461) has the ability to inject a downloaded DLL into a newly created rundll32.exe process.(Citation: Proofpoint TA505 October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27ccf817-33de-4d85-85e5-851f82e835e4`.
