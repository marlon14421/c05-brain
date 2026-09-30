---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "S0104"
stix_relationship_id: "relationship--5744b31d-6633-44ca-8170-17489fec124c"
---
# Relationship 6778: G0049 — uses → S0104

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0104 - netstat|S0104: netstat]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Palo Alto OilRig May 2016)(Citation: FireEye APT34 Dec 2017)(Citation: Symantec Crambus OCT 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5744b31d-6633-44ca-8170-17489fec124c`.
