---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1683.001"
stix_relationship_id: "relationship--4901a1a4-5db0-48a5-b046-23c8bc054f3a"
---
# Relationship 5825: G1052 — uses → T1683.001

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1683.001 - Written Content|T1683.001: Written Content]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has created fake social media accounts such as LinkedIn and Telegram accounts for their targeting efforts.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4901a1a4-5db0-48a5-b046-23c8bc054f3a`.
