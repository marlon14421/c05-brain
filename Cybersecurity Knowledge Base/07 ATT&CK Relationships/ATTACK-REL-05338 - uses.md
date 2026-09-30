---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1018"
stix_relationship_id: "relationship--e1f4c08f-b5b1-4d62-8f1c-75f4302b0bce"
---
# Relationship 5338: S0140 — uses → T1018

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) scans the C-class subnet of the IPs on the victim's interfaces.(Citation: FireEye Shamoon Nov 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1f4c08f-b5b1-4d62-8f1c-75f4302b0bce`.
