---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0088"
target_object: "T1518.001"
stix_relationship_id: "relationship--95a1ac52-e022-4c81-96cc-b7b39ca776d3"
---
# Relationship 7267: S0088 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0088 - Kasidet|S0088: Kasidet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kasidet](https://attack.mitre.org/software/S0088) has the ability to identify any anti-virus installed on the infected system.(Citation: Zscaler Kasidet)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95a1ac52-e022-4c81-96cc-b7b39ca776d3`.
