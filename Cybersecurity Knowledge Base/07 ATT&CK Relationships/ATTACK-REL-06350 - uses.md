---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1189"
stix_relationship_id: "relationship--5253d038-08a8-4d17-9549-bbcf67c37603"
---
# Relationship 6350: G0035 — uses → T1189

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has compromised targets via strategic web compromise (SWC) utilizing a custom exploit kit.(Citation: Secureworks IRON LIBERTY July 2019)(Citation: US-CERT TA18-074A)(Citation: Gigamon Berserk Bear October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5253d038-08a8-4d17-9549-bbcf67c37603`.
