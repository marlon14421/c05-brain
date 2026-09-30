---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0008"
target_object: "T1036.005"
stix_relationship_id: "relationship--bbf116bf-6f8a-44f4-9d98-db6ccbbff333"
---
# Relationship 8935: G0008 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0008 - Carbanak|G0008: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbanak](https://attack.mitre.org/groups/G0008) has named malware "svchost.exe," which is the name of the Windows shared service host program.(Citation: Kaspersky Carbanak)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bbf116bf-6f8a-44f4-9d98-db6ccbbff333`.
