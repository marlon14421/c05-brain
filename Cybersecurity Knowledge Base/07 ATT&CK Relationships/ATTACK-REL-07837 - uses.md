---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0531"
target_object: "T1059.005"
stix_relationship_id: "relationship--03a8b070-a7dd-43b0-a044-1cf9f999475b"
---
# Relationship 7837: S0531 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0531 - Grandoreiro|S0531: Grandoreiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Grandoreiro](https://attack.mitre.org/software/S0531) can use VBScript to execute malicious code.(Citation: Securelist Brazilian Banking Malware July 2020)(Citation: ESET Grandoreiro April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03a8b070-a7dd-43b0-a044-1cf9f999475b`.
