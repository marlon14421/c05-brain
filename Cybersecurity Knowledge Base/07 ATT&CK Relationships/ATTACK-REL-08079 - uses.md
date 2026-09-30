---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0004"
target_object: "T1090.003"
stix_relationship_id: "relationship--2b6b93eb-6664-4a70-82a9-e56a416b9e61"
---
# Relationship 8079: C0004 — uses → T1090.003

**Source object:** [[01 ATT&CK/C0004 - CostaRicto|C0004: CostaRicto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [CostaRicto](https://attack.mitre.org/campaigns/C0004), the threat actors used a layer of proxies to manage C2 communications.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b6b93eb-6664-4a70-82a9-e56a416b9e61`.
