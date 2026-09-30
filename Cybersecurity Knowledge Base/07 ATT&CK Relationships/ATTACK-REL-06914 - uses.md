---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1197"
target_object: "T1036.005"
stix_relationship_id: "relationship--d62b68f1-d58d-463e-b7a4-858f196bf8ce"
---
# Relationship 6914: S1197 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1197 - GoBear|S1197: GoBear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoBear](https://attack.mitre.org/software/S1197) is installed through droppers masquerading as legitimate, signed software installers.(Citation: Symantec Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d62b68f1-d58d-463e-b7a4-858f196bf8ce`.
