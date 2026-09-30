---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0071"
target_object: "S0104"
stix_relationship_id: "relationship--3d988f8f-2448-409c-ac41-4a507bb8cf23"
---
# Relationship 8074: G0071 — uses → S0104

**Source object:** [[01 ATT&CK/G0071 - Orangeworm|G0071: Orangeworm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0104 - netstat|S0104: netstat]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Orangeworm April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d988f8f-2448-409c-ac41-4a507bb8cf23`.
