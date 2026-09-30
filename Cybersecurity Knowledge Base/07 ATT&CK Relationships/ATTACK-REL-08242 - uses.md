---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0018"
target_object: "T1036.005"
stix_relationship_id: "relationship--4da943df-a7dc-499f-a8b7-ca8d298d8ff6"
---
# Relationship 8242: G0018 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0018 - admin@338|G0018: admin@338]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[admin@338](https://attack.mitre.org/groups/G0018) actors used the following command to rename one of their tools to a benign file name: ren "%temp%\upload" audiodg.exe (Citation: FireEye admin@338)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4da943df-a7dc-499f-a8b7-ca8d298d8ff6`.
