---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0071"
target_object: "S0099"
stix_relationship_id: "relationship--cc6e0159-1216-4ca5-ac5c-55e961878785"
---
# Relationship 8412: G0071 — uses → S0099

**Source object:** [[01 ATT&CK/G0071 - Orangeworm|G0071: Orangeworm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0099 - Arp|S0099: Arp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Orangeworm April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc6e0159-1216-4ca5-ac5c-55e961878785`.
