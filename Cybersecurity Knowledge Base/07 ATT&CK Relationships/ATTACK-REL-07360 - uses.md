---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0365"
target_object: "T1021.002"
stix_relationship_id: "relationship--ddf5cb3a-6cfa-40c8-8992-396329632f14"
---
# Relationship 7360: S0365 — uses → T1021.002

**Source object:** [[01 ATT&CK/S0365 - Olympic Destroyer|S0365: Olympic Destroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Olympic Destroyer](https://attack.mitre.org/software/S0365) uses [PsExec](https://attack.mitre.org/software/S0029) to interact with the ADMIN$ network share to execute commands on remote systems.(Citation: Talos Olympic Destroyer 2018)(Citation: PsExec Russinovich)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ddf5cb3a-6cfa-40c8-8992-396329632f14`.
