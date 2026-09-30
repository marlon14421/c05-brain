---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1063"
target_object: "T1102"
stix_relationship_id: "relationship--c1b5996f-e0f9-4986-9ee1-c5c9dc85d8e5"
---
# Relationship 8848: S1063 — uses → T1102

**Source object:** [[01 ATT&CK/S1063 - Brute Ratel C4|S1063: Brute Ratel C4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Brute Ratel C4](https://attack.mitre.org/software/S1063) can use legitimate websites for external C2 channels including Slack, Discord, and MS Teams.(Citation: Palo Alto Brute Ratel July 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1b5996f-e0f9-4986-9ee1-c5c9dc85d8e5`.
