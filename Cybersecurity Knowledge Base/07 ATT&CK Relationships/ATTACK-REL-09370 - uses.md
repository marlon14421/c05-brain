---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1039"
target_object: "T1036.005"
stix_relationship_id: "relationship--5df34449-b814-4580-a32c-d02f25cd8fe4"
---
# Relationship 9370: G1039 — uses → T1036.005

**Source object:** [[01 ATT&CK/G1039 - RedCurl|G1039: RedCurl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedCurl](https://attack.mitre.org/groups/G1039) mimicked legitimate file names and scheduled tasks, e.g. ` MicrosoftCurrentupdatesCheck` and `MdMMaintenenceTask` to mask malicious files and scheduled tasks.(Citation: group-ib_redcurl1)(Citation: group-ib_redcurl2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5df34449-b814-4580-a32c-d02f25cd8fe4`.
