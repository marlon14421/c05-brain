---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1011"
target_object: "T1036.005"
stix_relationship_id: "relationship--388e6809-55d3-4689-93b1-ddd9058b965c"
---
# Relationship 6087: S1011 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1011 - Tarrask|S1011: Tarrask]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tarrask](https://attack.mitre.org/software/S1011) has masqueraded as executable files such as `winupdate.exe`, `date.exe`, or `win.exe`.(Citation: Tarrask scheduled task)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--388e6809-55d3-4689-93b1-ddd9058b965c`.
