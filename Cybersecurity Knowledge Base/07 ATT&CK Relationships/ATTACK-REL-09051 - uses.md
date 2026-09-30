---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1237"
target_object: "T1055.005"
stix_relationship_id: "relationship--62ac011c-c2de-4049-84b2-0f3e773a73f1"
---
# Relationship 9051: S1237 — uses → T1055.005

**Source object:** [[01 ATT&CK/S1237 - CANONSTAGER|S1237: CANONSTAGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.005 - Thread Local Storage|T1055.005: Thread Local Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CANONSTAGER](https://attack.mitre.org/software/S1237) uses the Thread Local Storage (TLS) array data structure to store function addresses resolved by its custom API hashing algorithm. The function addresses are later called throughout the binary from offsets into the TLS array.(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62ac011c-c2de-4049-84b2-0f3e773a73f1`.
