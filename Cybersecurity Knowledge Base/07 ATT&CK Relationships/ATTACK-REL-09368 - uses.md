---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0196"
target_object: "T1518.001"
stix_relationship_id: "relationship--3c0cb507-2bf0-46ab-b5c2-ba2865397722"
---
# Relationship 9368: S0196 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0196 - PUNCHBUGGY|S0196: PUNCHBUGGY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUNCHBUGGY](https://attack.mitre.org/software/S0196) can gather AVs registered in the system.(Citation: Morphisec ShellTea June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c0cb507-2bf0-46ab-b5c2-ba2865397722`.
