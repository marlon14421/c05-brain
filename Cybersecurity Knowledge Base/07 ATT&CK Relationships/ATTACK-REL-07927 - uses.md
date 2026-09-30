---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1529"
stix_relationship_id: "relationship--dc81d3d6-c3e6-4f95-8143-e2da3ab5232a"
---
# Relationship 7927: G1051 — uses → T1529

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has manually turned off and encrypted virtual machines.(Citation: CISA Medusa Group Medusa Ransomware March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc81d3d6-c3e6-4f95-8143-e2da3ab5232a`.
