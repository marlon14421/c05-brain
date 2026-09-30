---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1505.003"
stix_relationship_id: "relationship--b1de5210-fbd9-4439-8d1a-bc400054d0ad"
---
# Relationship 9470: G0016 — uses → T1505.003

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has installed web shells on exploited Microsoft Exchange servers.(Citation: Cybersecurity Advisory SVR TTP May 2021)(Citation: Mandiant APT29 Eye Spy Email Nov 22)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1de5210-fbd9-4439-8d1a-bc400054d0ad`.
