---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0646"
target_object: "T1005"
stix_relationship_id: "relationship--60855df0-b2f5-46ed-ba9d-09bdfd7d1ac6"
---
# Relationship 7366: S0646 — uses → T1005

**Source object:** [[01 ATT&CK/S0646 - SpicyOmelette|S0646: SpicyOmelette]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpicyOmelette](https://attack.mitre.org/software/S0646) has collected data and other information from a compromised host.(Citation: Secureworks GOLD KINGSWOOD September 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60855df0-b2f5-46ed-ba9d-09bdfd7d1ac6`.
