---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0006"
target_object: "T1087.001"
stix_relationship_id: "relationship--d014d8e1-b12e-4b85-84ee-ff4338c54393"
---
# Relationship 8459: G0006 — uses → T1087.001

**Source object:** [[01 ATT&CK/G0006 - APT1|G0006: APT1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT1](https://attack.mitre.org/groups/G0006) used the commands net localgroup , net user , and net group to find accounts on the system.(Citation: Mandiant APT1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d014d8e1-b12e-4b85-84ee-ff4338c54393`.
