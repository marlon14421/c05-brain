---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0625"
target_object: "T1036.005"
stix_relationship_id: "relationship--ed136275-95b7-4f46-914c-a7f964558278"
---
# Relationship 7218: S0625 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0625 - Cuba|S0625: Cuba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cuba](https://attack.mitre.org/software/S0625) has been disguised as legitimate 360 Total Security Antivirus and OpenVPN programs.(Citation: McAfee Cuba April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed136275-95b7-4f46-914c-a7f964558278`.
