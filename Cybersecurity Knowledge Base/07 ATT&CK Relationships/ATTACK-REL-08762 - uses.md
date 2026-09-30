---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1236"
target_object: "T1036.005"
stix_relationship_id: "relationship--7e3afacc-85c0-49a3-ae44-0a57c7ee0427"
---
# Relationship 8762: S1236 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1236 - CLAIMLOADER|S1236: CLAIMLOADER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CLAIMLOADER](https://attack.mitre.org/software/S1236) has imitated legitimate software directories through the creation and storage of the EXE and DLL in `C:\ProgramData\` and the use of legitimate looking names of software.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e3afacc-85c0-49a3-ae44-0a57c7ee0427`.
