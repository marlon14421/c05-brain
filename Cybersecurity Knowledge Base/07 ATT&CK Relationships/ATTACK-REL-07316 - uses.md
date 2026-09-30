---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1584.005"
stix_relationship_id: "relationship--5f7da78d-8d46-43db-945d-14bdc316d504"
---
# Relationship 7316: G1017 — uses → T1584.005

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.005 - Botnet|T1584.005: Botnet]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has used compromised Cisco and NETGEAR end-of-life SOHO routers implanted with KV Botnet malware to support operations.(Citation: CISA AA24-038A PRC Critical Infrastructure February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f7da78d-8d46-43db-945d-14bdc316d504`.
