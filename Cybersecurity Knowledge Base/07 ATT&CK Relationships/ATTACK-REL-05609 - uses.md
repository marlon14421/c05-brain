---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0043"
target_object: "T1113"
stix_relationship_id: "relationship--8e69c855-db70-4b5e-866b-f9ce0b786156"
---
# Relationship 5609: G0043 — uses → T1113

**Source object:** [[01 ATT&CK/G0043 - Group5|G0043: Group5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Malware used by [Group5](https://attack.mitre.org/groups/G0043) is capable of watching the victim's screen.(Citation: Citizen Lab Group5)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8e69c855-db70-4b5e-866b-f9ce0b786156`.
