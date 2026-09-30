---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "S0187"
stix_relationship_id: "relationship--f52f1b34-a96a-45a0-8cc0-2f138a3f1257"
---
# Relationship 5406: G0060 — uses → S0187

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0187 - Daserf|S0187: Daserf]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Trend Micro Daserf Nov 2017)(Citation: Symantec Tick Apr 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f52f1b34-a96a-45a0-8cc0-2f138a3f1257`.
