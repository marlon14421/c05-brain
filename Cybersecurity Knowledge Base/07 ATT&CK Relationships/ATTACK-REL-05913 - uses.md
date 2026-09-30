---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0350"
target_object: "T1021.002"
stix_relationship_id: "relationship--1ec9706f-7faa-466d-afd0-97cc71714f7b"
---
# Relationship 5913: S0350 — uses → T1021.002

**Source object:** [[01 ATT&CK/S0350 - zwShell|S0350: zwShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[zwShell](https://attack.mitre.org/software/S0350) has been copied over network shares to move laterally.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ec9706f-7faa-466d-afd0-97cc71714f7b`.
