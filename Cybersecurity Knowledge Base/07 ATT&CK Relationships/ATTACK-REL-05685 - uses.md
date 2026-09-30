---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1217"
stix_relationship_id: "relationship--9cf53303-770b-4de2-bbf2-3d79d5432f93"
---
# Relationship 5685: S1240 — uses → T1217

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) can collect information from browsers and browser extensions.(Citation: Splunk RedLine Stealer June 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cf53303-770b-4de2-bbf2-3d79d5432f93`.
