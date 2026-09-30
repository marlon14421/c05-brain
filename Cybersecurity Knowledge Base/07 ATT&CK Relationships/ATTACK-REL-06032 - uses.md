---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1574.013"
stix_relationship_id: "relationship--fa5b5933-f9e3-4bbb-b734-f1c5984ded97"
---
# Relationship 6032: S0182 — uses → T1574.013

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.013 - KernelCallbackTable|T1574.013: KernelCallbackTable]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) has used the KernelCallbackTable to hijack the execution flow of a process by replacing the __fnDWORD function with the address of a created [Asynchronous Procedure Call](https://attack.mitre.org/techniques/T1055/004) stub routine.(Citation: FinFisher exposed )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa5b5933-f9e3-4bbb-b734-f1c5984ded97`.
