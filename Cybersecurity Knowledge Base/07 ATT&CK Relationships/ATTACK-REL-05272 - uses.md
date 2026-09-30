---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0353"
target_object: "T1036.005"
stix_relationship_id: "relationship--67f1d68d-fe0f-4e65-8b2a-f614fda68e3c"
---
# Relationship 5272: S0353 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0353 - NOKKI|S0353: NOKKI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOKKI](https://attack.mitre.org/software/S0353) is written to %LOCALAPPDATA%\MicroSoft Updatea\svServiceUpdate.exe prior being executed in a new process in an apparent attempt to masquerade as a legitimate folder and file.(Citation: Unit 42 NOKKI Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67f1d68d-fe0f-4e65-8b2a-f614fda68e3c`.
