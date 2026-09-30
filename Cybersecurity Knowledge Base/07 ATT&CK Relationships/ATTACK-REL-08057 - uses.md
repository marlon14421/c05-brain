---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0071"
target_object: "T1071.001"
stix_relationship_id: "relationship--1d90aad5-e0fb-4a8c-862a-71d3db99bae9"
---
# Relationship 8057: G0071 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0071 - Orangeworm|G0071: Orangeworm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Orangeworm](https://attack.mitre.org/groups/G0071) has used HTTP for C2.(Citation: Symantec Orangeworm IOCs April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d90aad5-e0fb-4a8c-862a-71d3db99bae9`.
