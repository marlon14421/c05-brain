---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1021"
target_object: "T1078.002"
stix_relationship_id: "relationship--6e478b50-57b3-418b-b866-8441be0036b6"
---
# Relationship 5603: G1021 — uses → T1078.002

**Source object:** [[01 ATT&CK/G1021 - Cinnamon Tempest|G1021: Cinnamon Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cinnamon Tempest](https://attack.mitre.org/groups/G1021) has obtained highly privileged credentials such as domain administrator in order to deploy malware.(Citation: Microsoft Ransomware as a Service)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e478b50-57b3-418b-b866-8441be0036b6`.
