---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1138"
target_object: "T1204.001"
stix_relationship_id: "relationship--7a75776c-22e1-4227-9c7a-8531f9ce6c5e"
---
# Relationship 9692: S1138 — uses → T1204.001

**Source object:** [[01 ATT&CK/S1138 - Gootloader|S1138: Gootloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gootloader](https://attack.mitre.org/software/S1138) has been executed through malicious links presented to users as internet search results.(Citation: Sophos Gootloader)(Citation: SentinelOne Gootloader June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a75776c-22e1-4227-9c7a-8531f9ce6c5e`.
