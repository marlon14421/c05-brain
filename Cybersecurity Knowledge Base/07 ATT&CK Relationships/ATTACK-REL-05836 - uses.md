---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1069.002"
stix_relationship_id: "relationship--3e17459a-edb2-471c-87b0-1315f3500ab6"
---
# Relationship 5836: G1017 — uses → T1069.002

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has run `net group` in compromised environments to discover domain groups.(Citation: Secureworks BRONZE SILHOUETTE May 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e17459a-edb2-471c-87b0-1315f3500ab6`.
