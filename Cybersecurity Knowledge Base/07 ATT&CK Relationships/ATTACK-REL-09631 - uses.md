---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1036.005"
stix_relationship_id: "relationship--8e824b6e-a0b7-4a57-9a7e-89b2c390beec"
---
# Relationship 9631: S0013 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) has been disguised as legitimate Adobe and PotPlayer files.(Citation: Proofpoint TA416 Europe March 2022) [PlugX](https://attack.mitre.org/software/S0013) has also imitated legitimate software directories and file names through the creation and storage of a legitimate EXE and the malicious DLLs.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Sophos PlugX September 2022)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8e824b6e-a0b7-4a57-9a7e-89b2c390beec`.
