---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1219"
stix_relationship_id: "relationship--14e8774f-a443-4065-b44d-5bb13b467c7c"
---
# Relationship 6895: S0148 — uses → T1219

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RTM](https://attack.mitre.org/software/S0148) has the capability to download a VNC module from command and control (C2).(Citation: ESET RTM Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14e8774f-a443-4065-b44d-5bb13b467c7c`.
