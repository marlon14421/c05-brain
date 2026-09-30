---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1032"
target_object: "T1036.005"
stix_relationship_id: "relationship--40b50ac5-b1c1-4f80-b350-460cc0ed9f9f"
---
# Relationship 7401: S1032 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1032 - PyDCrypt|S1032: PyDCrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PyDCrypt](https://attack.mitre.org/software/S1032) has dropped [DCSrv](https://attack.mitre.org/software/S1033) under the `svchost.exe` name to disk.(Citation: Checkpoint MosesStaff Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40b50ac5-b1c1-4f80-b350-460cc0ed9f9f`.
