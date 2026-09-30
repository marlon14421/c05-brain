---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0021"
target_object: "T1059.007"
stix_relationship_id: "relationship--cbba2f85-d5f4-4306-a219-5eea6c59dbb6"
---
# Relationship 7040: G0021 — uses → T1059.007

**Source object:** [[01 ATT&CK/G0021 - Molerats|G0021: Molerats]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Molerats](https://attack.mitre.org/groups/G0021) used various implants, including those built with JS, on target machines.(Citation: Kaspersky MoleRATs April 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbba2f85-d5f4-4306-a219-5eea6c59dbb6`.
