---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1082"
stix_relationship_id: "relationship--aa4acffb-0b5c-48b3-b0c4-d321e6ae842d"
---
# Relationship 5895: S9043 — uses → T1082

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has gathered system information of victim hosts through the use of common discovery commands to include `hostname`, `uname-a` and `printenv`.(Citation: Trend Micro TeamPCP MAY 2026) [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also conducted system checks of the victim device to include enumerating the system type and the number of CPUs operating on victim host.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa4acffb-0b5c-48b3-b0c4-d321e6ae842d`.
