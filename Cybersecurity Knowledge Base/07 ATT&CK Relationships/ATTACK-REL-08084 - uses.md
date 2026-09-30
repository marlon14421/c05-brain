---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0167"
target_object: "T1055.001"
stix_relationship_id: "relationship--47415cec-25f8-4425-9125-157e1637a687"
---
# Relationship 8084: S0167 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0167 - Matryoshka|S0167: Matryoshka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Matryoshka](https://attack.mitre.org/software/S0167) uses reflective DLL injection to inject the malicious library and execute the RAT.(Citation: CopyKittens Nov 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47415cec-25f8-4425-9125-157e1637a687`.
