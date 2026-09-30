---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1028"
target_object: "T1082"
stix_relationship_id: "relationship--c707d09b-1b36-4a1c-99be-c905fdd3ff6b"
---
# Relationship 5701: S1028 — uses → T1082

**Source object:** [[01 ATT&CK/S1028 - Action RAT|S1028: Action RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Action RAT](https://attack.mitre.org/software/S1028) has the ability to collect the hostname, OS version, and OS architecture of an infected host.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c707d09b-1b36-4a1c-99be-c905fdd3ff6b`.
