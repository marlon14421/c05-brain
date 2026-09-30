---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0249"
target_object: "T1071.001"
stix_relationship_id: "relationship--c233f12f-cfa1-4f2a-ba56-ca1980806f4e"
---
# Relationship 8313: S0249 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0249 - Gold Dragon|S0249: Gold Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gold Dragon](https://attack.mitre.org/software/S0249) uses HTTP for communication to the control servers.(Citation: McAfee Gold Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c233f12f-cfa1-4f2a-ba56-ca1980806f4e`.
