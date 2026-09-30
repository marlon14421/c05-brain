---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1552.001"
stix_relationship_id: "relationship--f9234d49-433d-41b2-ac26-7e9c899e6076"
---
# Relationship 8099: G1015 — uses → T1552.001

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) Spider searches for credential storage documentation on a compromised host.(Citation: CISA Scattered Spider Advisory November 2023)(Citation: Mandiant UNC3944 May 2025)(Citation: CrowdStrike Scattered Spider JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9234d49-433d-41b2-ac26-7e9c899e6076`.
