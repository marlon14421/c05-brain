---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1673"
stix_relationship_id: "relationship--2d1a9941-df94-4e1f-9132-80b052bcb1fc"
---
# Relationship 5625: G1048 — uses → T1673

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1673 - Virtual Machine Discovery|T1673: Virtual Machine Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has used scripts to enumerate ESXi hypervisors and their guest VMs.(Citation: Google Cloud Threat Intelligence VMWare ESXi Zero-Day 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d1a9941-df94-4e1f-9132-80b052bcb1fc`.
