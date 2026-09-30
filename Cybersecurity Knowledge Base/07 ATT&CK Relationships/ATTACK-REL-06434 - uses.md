---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1070.004"
stix_relationship_id: "relationship--c56a229c-f033-4a51-ad5c-251dff28b87e"
---
# Relationship 6434: S0251 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) has a command to delete files and directories.(Citation: ESET Zebrocy Nov 2018)(Citation: ESET Zebrocy May 2019)(Citation: CISA Zebrocy Oct 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c56a229c-f033-4a51-ad5c-251dff28b87e`.
