---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0193"
target_object: "T1005"
stix_relationship_id: "relationship--9420e9de-cc4c-4d5c-b40f-02c57dcc4fd9"
---
# Relationship 9915: S0193 — uses → T1005

**Source object:** [[01 ATT&CK/S0193 - Forfiles|S0193: Forfiles]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Forfiles](https://attack.mitre.org/software/S0193) can be used to act on (ex: copy, move, etc.) files/directories in a system during (ex: copy files into a staging area before).(Citation: Überwachung APT28 Forfiles June 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9420e9de-cc4c-4d5c-b40f-02c57dcc4fd9`.
