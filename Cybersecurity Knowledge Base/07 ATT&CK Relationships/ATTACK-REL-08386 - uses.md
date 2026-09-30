---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9025"
target_object: "T1564"
stix_relationship_id: "relationship--d6a855be-0b7c-4a30-8759-e9506ca420b7"
---
# Relationship 8386: S9025 — uses → T1564

**Source object:** [[01 ATT&CK/S9025 - NOOPLDR|S9025: NOOPLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564 - Hide Artifacts|T1564: Hide Artifacts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOOPLDR](https://attack.mitre.org/software/S9025) can hide services used to aid execution.(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6a855be-0b7c-4a30-8759-e9506ca420b7`.
