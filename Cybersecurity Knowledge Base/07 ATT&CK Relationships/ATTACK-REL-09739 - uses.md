---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1083"
stix_relationship_id: "relationship--204086ef-c546-47fd-8844-b8af57085f26"
---
# Relationship 9739: G1051 — uses → T1083

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has searched for files within the victim environment for encryption and exfiltration.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: CISA Medusa Group Medusa Ransomware March 2025)(Citation: Security Scorecard Medusa Ransomware January 2024) [Medusa Group](https://attack.mitre.org/groups/G1051) has also identified files associated with remote management services.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: CISA Medusa Group Medusa Ransomware March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--204086ef-c546-47fd-8844-b8af57085f26`.
