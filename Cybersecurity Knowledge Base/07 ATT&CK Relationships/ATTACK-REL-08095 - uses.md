---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1486"
stix_relationship_id: "relationship--47a9cbf2-d225-4cdd-ad8a-760e2c32f6cb"
---
# Relationship 8095: G1015 — uses → T1486

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has used [BlackCat](https://attack.mitre.org/software/S1068) and DragonForce ransomware to encrypt files including on VMWare ESXi servers.(Citation: CISA Scattered Spider Advisory November 2023)(Citation: MSTIC Octo Tempest Operations October 2023)(Citation: CrowdStrike Scattered Spider JUL 2025)(Citation: Mandiant VMware vSphere JUL 2025)(Citation: Check Point Scattered Spider JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47a9cbf2-d225-4cdd-ad8a-760e2c32f6cb`.
