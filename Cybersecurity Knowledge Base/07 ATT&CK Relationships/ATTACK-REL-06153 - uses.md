---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1021.002"
stix_relationship_id: "relationship--53d7b242-3ed6-4281-9829-e25d425e28fe"
---
# Relationship 6153: S0089 — uses → T1021.002

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackEnergy](https://attack.mitre.org/software/S0089) has run a plug-in on a victim to spread through the local network by using [PsExec](https://attack.mitre.org/software/S0029) and accessing admin shares.(Citation: Securelist BlackEnergy Nov 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53d7b242-3ed6-4281-9829-e25d425e28fe`.
