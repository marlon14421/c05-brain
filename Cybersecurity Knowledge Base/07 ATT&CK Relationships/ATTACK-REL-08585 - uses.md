---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0504"
target_object: "T1021.002"
stix_relationship_id: "relationship--f7ebcffb-0397-430b-a19f-0f2f842d79ed"
---
# Relationship 8585: S0504 — uses → T1021.002

**Source object:** [[01 ATT&CK/S0504 - Anchor|S0504: Anchor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Anchor](https://attack.mitre.org/software/S0504) can support windows execution via SMB shares.(Citation: Medium Anchor DNS July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7ebcffb-0397-430b-a19f-0f2f842d79ed`.
