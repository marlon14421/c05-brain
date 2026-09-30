---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "S1133"
stix_relationship_id: "relationship--cdec9832-31e5-472f-ac45-7667c77b8acd"
---
# Relationship 8644: G1030 — uses → S1133

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1133 - Apostle|S1133: Apostle]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) has used [Apostle](https://attack.mitre.org/software/S1133) as both a wiper and ransomware-like effects capability in intrusions.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cdec9832-31e5-472f-ac45-7667c77b8acd`.
