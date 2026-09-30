---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "T1036.004"
stix_relationship_id: "relationship--887465a0-6818-4e79-b86d-b83d3a0f39eb"
---
# Relationship 7609: G0019 — uses → T1036.004

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Naikon](https://attack.mitre.org/groups/G0019) renamed a malicious service taskmgr to appear to be a legitimate version of Task Manager.(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--887465a0-6818-4e79-b86d-b83d3a0f39eb`.
