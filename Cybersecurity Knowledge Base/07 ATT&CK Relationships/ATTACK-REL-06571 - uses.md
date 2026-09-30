---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1003.003"
stix_relationship_id: "relationship--8b8e829b-9f29-4677-8f22-f63b6c49a115"
---
# Relationship 6571: G1051 — uses → T1003.003

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has accessed the ntds.dit file to engage in credential dumping.(Citation: Broadcom Medusa Ransomware Medusa Group March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b8e829b-9f29-4677-8f22-f63b6c49a115`.
