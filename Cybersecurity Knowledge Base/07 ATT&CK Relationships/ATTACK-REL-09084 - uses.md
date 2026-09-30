---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1009"
target_object: "T1027.013"
stix_relationship_id: "relationship--a56ece45-a76c-4b19-8999-6dde50b48409"
---
# Relationship 9084: G1009 — uses → T1027.013

**Source object:** [[01 ATT&CK/G1009 - Moses Staff|G1009: Moses Staff]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moses Staff](https://attack.mitre.org/groups/G1009) has used obfuscated web shells in their operations.(Citation: Checkpoint MosesStaff Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a56ece45-a76c-4b19-8999-6dde50b48409`.
