---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0057"
target_object: "T1078"
stix_relationship_id: "relationship--4e78a70d-13b0-4539-bc43-0f45417b91c2"
---
# Relationship 7152: C0057 — uses → T1078

**Source object:** [[01 ATT&CK/C0057 - 3CX Supply Chain Attack|C0057: 3CX Supply Chain Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [3CX Supply Chain Attack](https://attack.mitre.org/campaigns/C0057), [AppleJeus](https://attack.mitre.org/groups/G1049) has gained access to the 3CX corporate environment through legitimate VPN credentials.(Citation: 3cx official statement 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e78a70d-13b0-4539-bc43-0f45417b91c2`.
