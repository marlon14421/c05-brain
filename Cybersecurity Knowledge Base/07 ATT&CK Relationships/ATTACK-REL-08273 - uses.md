---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1021"
target_object: "T1021.002"
stix_relationship_id: "relationship--c6cf559e-1ead-4fba-9c61-72e33bae10e5"
---
# Relationship 8273: G1021 — uses → T1021.002

**Source object:** [[01 ATT&CK/G1021 - Cinnamon Tempest|G1021: Cinnamon Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cinnamon Tempest](https://attack.mitre.org/groups/G1021) has used SMBexec for lateral movement.(Citation: Sygnia Emperor Dragonfly October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6cf559e-1ead-4fba-9c61-72e33bae10e5`.
