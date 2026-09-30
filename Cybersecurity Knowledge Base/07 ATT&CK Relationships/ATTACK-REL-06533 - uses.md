---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0581"
target_object: "T1036.004"
stix_relationship_id: "relationship--8d305ed1-3ac5-4431-ae3c-766d430d9d5f"
---
# Relationship 6533: S0581 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0581 - IronNetInjector|S0581: IronNetInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IronNetInjector](https://attack.mitre.org/software/S0581) has been disguised as a legitimate service using the name PythonUpdateSrvc.(Citation: Unit 42 IronNetInjector February 2021 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d305ed1-3ac5-4431-ae3c-766d430d9d5f`.
