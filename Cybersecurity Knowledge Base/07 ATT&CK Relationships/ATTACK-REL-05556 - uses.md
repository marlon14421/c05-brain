---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0200"
target_object: "T1547.004"
stix_relationship_id: "relationship--4536c335-5138-42d1-8f1e-63dee7cb17ab"
---
# Relationship 5556: S0200 — uses → T1547.004

**Source object:** [[01 ATT&CK/S0200 - Dipsind|S0200: Dipsind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.004 - Winlogon Helper DLL|T1547.004: Winlogon Helper DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [Dipsind](https://attack.mitre.org/software/S0200) variant registers as a Winlogon Event Notify DLL to establish persistence.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4536c335-5138-42d1-8f1e-63dee7cb17ab`.
