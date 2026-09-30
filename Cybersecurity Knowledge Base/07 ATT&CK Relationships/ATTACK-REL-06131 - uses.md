---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1100"
target_object: "T1029"
stix_relationship_id: "relationship--6a822142-8cf6-4830-881a-be8630a4bf90"
---
# Relationship 6131: S1100 — uses → T1029

**Source object:** [[01 ATT&CK/S1100 - Ninja|S1100: Ninja]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1029 - Scheduled Transfer|T1029: Scheduled Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ninja](https://attack.mitre.org/software/S1100) can configure its agent to work only in specific time frames.(Citation: Kaspersky ToddyCat June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a822142-8cf6-4830-881a-be8630a4bf90`.
