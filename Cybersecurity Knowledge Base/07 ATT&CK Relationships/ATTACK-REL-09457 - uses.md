---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1050"
target_object: "T1036.005"
stix_relationship_id: "relationship--095d33b5-523d-40ae-aad9-448910d527d3"
---
# Relationship 9457: S1050 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1050 - PcShare|S1050: PcShare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PcShare](https://attack.mitre.org/software/S1050) has been named `wuauclt.exe` to appear as the legitimate Windows Update AutoUpdate Client.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--095d33b5-523d-40ae-aad9-448910d527d3`.
