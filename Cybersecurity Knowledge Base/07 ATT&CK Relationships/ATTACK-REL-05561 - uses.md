---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0170"
target_object: "T1057"
stix_relationship_id: "relationship--5bb90849-cdfe-4cc0-9ca3-128f17b2a1d1"
---
# Relationship 5561: S0170 — uses → T1057

**Source object:** [[01 ATT&CK/S0170 - Helminth|S0170: Helminth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Helminth](https://attack.mitre.org/software/S0170) has used [Tasklist](https://attack.mitre.org/software/S0057) to get information on processes.(Citation: Unit 42 Playbook Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5bb90849-cdfe-4cc0-9ca3-128f17b2a1d1`.
